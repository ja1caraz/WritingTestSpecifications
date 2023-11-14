# WritingTestSpecifications

Unit Test

Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be an array
Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be equal to [-1, 1, 3, 9, 15]
Expect concatOdds([], [2, 4, 6]) to be an empty array

Unexpected Results

Expect concatOdds([1, 'a', 3], [4, 5, 6]) to be an error
Expect concatOdds([1, 2, 3], ['x', 'y', 'z']) to be an error
Expect concatOdds([1, 3, 3], [3, 1, 5]) to be equal to [1, 3, 5]
Expect concatOdds([7, 7, 7], [7, 7, 7]) to be equal to [7]


