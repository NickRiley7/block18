# block18

"Multiplication"
expect [action] to be [some result]
expect multiplication(2, 4) to be a number
expect multiplication(2, 4) to be equal to 8
expect multiplication("a", 4) to be an error
the multiplication function should only take two parameters.
the first parameter (num1) of the multiplication function should be a number.
the second parameter (num2) of the multiplication function should be a number.
the multiplication function should return num1 x num2;

"concatOdds"
concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])
should result in [-1, 1, 3, 9, 15]
the concatOdds function should take in two and only two parameters.
the first parameter (arr1) of the concatOdds function should be an array.
the second parameter (arr2) of the concatOdds function should be an array.
the values in the first parameter (arr1) of the concatOdds function should all be numbers.
the values in the second parameter (arr2) of the concatOdds function should all be numbers.
the concatOdds function should return one array.
the returned array of the concatOdds function should contain only numbers from both arr1 and arr2.
the returned array of the concatOdds function should contain no duplicate numbers.
the returned array of the concatOdds function should be in ascending order.

"Functional Test"
cart should allow user to check out as guest
cart should ask user if they want to make an account
cart should display message "cart empty" if cart is empty
price should be displayed upon starting check out
info boxes should be displayed for user to input info
steps should be listed for user to navigate to easily
order confirmation should be displayed upon completion of check out
cart([price] * [quantity])
should result in [final price]