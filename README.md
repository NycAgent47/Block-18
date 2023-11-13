# Block-18
 Project Block 18

 Writing Test Specifications 

 Multiplication Tests

 - Tested with positive numbers (multiplication (2, 3), expecting 6)
 - Tested with negative numbers (multiplication (-2, -3), expecting 6)
 - Tested with one positive number and one negative number (multiplication (-2, 3), expecting -6)
 - Tested with zero (multiplication (0, 4), expecting 0, multiplication (4, 0), expecting 0)

 ConcatOdds Tests

 - Tested with normal cases including positive and negative integers (concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]), expecting [-1, 1, 3, 9, 15])
 - Tested with one or both arrays being empty (concatOdds([], [1, 3, 5]), expecting [1, 3, 5])
 - Tested with arrays containing large numbers to check for any performance issues
 - Tested with null or undefined inputs

 Functional Tests (Shopping Cart Test)

 - Tested checkout process for a logged-in user
 - Tested process for a guest user
 - Tested prompt to create an account or log in for a guest user
 - Tested checkout with an empty cart (should either prevent checkout or notify the user that the cart is empty)
 - Tested checkout with a cart that has items but encounters an inventory issue (Example: item out of stock)
 - Tested the response time and performance of the checkout process

 Take in consideration that the tests should cover scenarios where the user changes their mind, edits the cart, or updates quantities during the checkout process
