footer: © Valor Software, 2018
slidenumbers: true
autoscale: true
build-lists: true

![](valor_software.png)

---

# Test-Driven-Development

## Stages
1. Add a test
2. Run all tests and see if the new test fails
3. Write a code
4. Run tests - they should be green
5. Add a test
6. ...
---
## Let's see how it's look's like:
    `‘![](TDD.png)’`
---
# A fly in the ointment
    `‘![](ointment.jpg)’`
---
## Look at basic test, and try to reach what this test do

    it('test validate function', () => {
        expect(ReferenceNumber.validate('1234567890123')).toBeFalsy();
        expect(ReferenceNumber.validate('1234567')).toBeFalsy();
        expect(ReferenceNumber.validate('12345678')).toBeTruthy();
 }
---
## Look at test, written with few "Best practices"

describe('check validation', () => {

    it('test short numbers', () => {
        const shortNumber = '1234567';
        expect(ReferenceNumber.validate(shortNumber)).toBeFalsy();
    };

    it('test long numbers', () => {
            const longNumber = '123456789012';
            expect(ReferenceNumber.validate(longNumber)).toBeFalsy();
    };

    it('test good numbers', () => {
                const goodNumber = '12345678';
                expect(ReferenceNumber.validate(goodNumber)).toBeTruthy();
    };
}
---