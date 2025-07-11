# Test Cases for Simple Calculator Application

## ✅ Valid Input Test Cases

| Test Case ID | Test Description | Preconditions | Test Steps | Expected Result |
|--------------|------------------|---------------|------------|-----------------|
| TC01 | Verify addition of two positive integers | Calculator is open | Enter 5 + 3 and press = | Output should be 8 |
| TC02 | Verify subtraction of two numbers | Calculator is open | Enter 9 - 4 and press = | Output should be 5 |
| TC03 | Verify multiplication of two positive numbers | Calculator is open | Enter 6 * 7 and press = | Output should be 42 |
| TC04 | Verify division of two numbers | Calculator is open | Enter 20 / 5 and press = | Output should be 4 |
| TC05 | Verify operation with decimal numbers | Calculator is open | Enter 5.5 + 2.3 and press = | Output should be 7.8 |
| TC06 | Verify operation with negative numbers | Calculator is open | Enter -5 * -4 and press = | Output should be 20 |
| TC07 | Verify BODMAS operation | Calculator is open | Enter 2 + 3 * 4 and press = | Output should be 14 |
| TC08 | Verify complex expression | Calculator is open | Enter (2 + 3) * 4 and press = | Output should be 20 |

---

## ❌ Invalid Input Test Cases

| Test Case ID | Test Description | Preconditions | Test Steps | Expected Result |
|--------------|------------------|---------------|------------|-----------------|
| TC09 | Division by zero | Calculator is open | Enter 9 / 0 and press = | Error message or 'Infinity' |
| TC10 | Input with letters | Calculator is open | Enter A + B and press = | Error or "Invalid Input" |
| TC11 | Input with special characters | Calculator is open | Enter 5 + @ and press = | Error or "Invalid Input" |
| TC12 | Empty input | Calculator is open | Press = without entering values | Error or "No Input" |
| TC13 | Multiple decimal points in number | Calculator is open | Enter 5..3 + 2 and press = | Error or "Invalid Number Format" |
