# B18-Writing-Test-

 Unit Tests for "multiplication" function:

1. Test if multiplication(2, 3) gives a number
2. Check if multiplication(2, 3) equals 6
3. Test if multiplication(-5, 4) equals -20
4. Make sure multiplication(0, 100) equals 0
5. See if multiplication(3.5, 2) equals 7
6. Check what happens if we do multiplication with a letter like multiplication("a", 3)
7. Try multiplication with letters on both sides like multiplication("x", "y")
8. Test multiplication(2, null) and multiplication(null, 3) to see if they give errors

 Unit Tests for "concatOdds" function:

1. Check if concatOdds works with two example arrays and gives [-1, 1, 3, 9, 15]
2. Test concatOdds with one empty array and one with numbers to see the result
3. Try concatOdds with one array full of odds and the other full of evens
4. Test if concatOdds works when both arrays have the same odd numbers multiple times
5. Check how concatOdds handles arrays of only even numbers
6. Test concatOdds with different combinations of odd and even numbers

 Functional Tests for shopping cart checkout feature:

1. Check what happens if the cart is empty - try to check out and see the message or prompt
2. Test the process of checking out as a guest and see if it prompts to create an account or log in
3. See if logged-in users can checkout directly without the prompt for account creation or login
4. Check each step during the checkout process - like reviewing the cart, entering an address, choosing payment, and confirming the order
5. Test unexpected things like checking out without items, entering wrong details, or leaving and coming back
6. Explore scenarios like applying discounts, handling out-of-stock items, and international shipping
7. Test things related to user accounts - like logging in during checkout or creating an account while checking out
