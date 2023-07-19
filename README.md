# credit-card-validation

Using the Luhn algorithm, this code determines whether a credit card number is legitimate or not. The Luhn algorithm is a set of mathematical calculations that are used to validate identity numbers such as credit card numbers. The code's calculations can be split down into the following steps:

1. Iterate to the left beginning with the farthest digit to the right, often known as the check digit.
2. Every other number is doubled as you iterate to the left (the check digit is not doubled). Subtract 9 from the value of the number if it is larger than 9 after doubling.
3. Add all of the numbers in the credit card number together.
4. If the total modulo 10 is zero (if the sum divided by ten gives a remainder of zero), then the credit card number is valid, otherwise, it’s invalid.
