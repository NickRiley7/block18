# block18
PART 1
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

PART 2
Unit tests
should recognize and display all players in lobby
should display "See Details" button for each player
 when "Display Details" is clicked players name, breed, and assigned team or unassigned should be displayed
 should display larger player picture
 should display back to main list button
 should list all teammates as current player when game is played in single player view
 should have a drop down menu to change team assignment of current player
 updates should appear in single player view and in roster without a refresh
should diplay "Remove" button
 "remove" button should remove player off the roster
 removed player's name should disappear from roster without a refresh
should diplay form to add new players
form should display two inputs
 one input should display players name
 one input should display players breed
form should display one button
 button should be a submit button
 button should submit the data and add the player to the roster
 extra input to provide an image url when adding a player
 image should be player's picture
updates should not require a refresh to display changes to roster

Integration tests
when user uses form to select player, correct player should be recognized
changes should be applied to correct player

Functonal tests
as a user, I should be able to utilize the forms to make changes to roster
all changes should update as they are made without a refresh

Acceptance test
user can use the forms to make changes to roster



