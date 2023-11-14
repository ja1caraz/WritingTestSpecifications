# WritingTestSpecifications

Unit Test for multiplication function

Expect multiplication(5, 8) to be a number
Expect multiplication(5, 3) to be equal to 15
Expect multiplication(-5, 5) to be equal to -25

Unit Test for concatOdds funciton

Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be an array
Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be equal to [-1, 1, 3, 9, 15]
Expect concatOdds([], [2, 4, 6]) to be an empty array

Unexpected error and douplicate Unit Test

Expect concatOdds([1, 'a', 3], [4, 5, 6]) to be an error
Expect concatOdds([1, 2, 3], ['x', 'y', 'z']) to be an error
Expect concatOdds([1, 3, 3], [3, 1, 5]) to be equal to [1, 3, 5]
Expect concatOdds([8, 8, 8], [8, 8, 8]) to be equal to [8]

Funtional Test for Check out Website

Expect guest user to be able to add items to the shopping cart.
Expect guest user to be able to proceed to checkout as a guest.
Expect logged-in user to be able to add items to the shopping cart.
Expect logged-in user to be able to proceed to checkout.
Expect user to be notified if attempting to proceed to checkout with an empty cart.
Expect the option to go back to shopping if the cart is empty.

