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
(<br>)should recognize and display all players in lobby  return
(<br>)should display "See Details" button for each player  return
 (<br>)when "Display Details" is clicked players name, breed, and assigned team or unassigned should be displayed  return
 (<br>)should display larger player picture  return
 (<br>)should display back to main list button  return
 (<br>)should list all teammates as current player when game is played in single player view  return
 (<br>)should have a drop down menu to change team assignment of current player  return
 (<br>)updates should appear in single player view and in roster without a refresh  return
(<br>)should diplay "Remove" button  return
(<br>) "remove" button should remove player off the roster  return
(<br>) removed player's name should disappear from roster without a refresh  return
(<br>)should diplay form to add new players  return
(<br>)form should display two inputs  return
 (<br>) one input should display players name  return
 (<br>)one input should display players breed  return
(<br>)form should display one button  return
 (<br>)button should be a submit button  return
 (<br>)button should submit the data and add the player to the roster  return
 (<br>)extra input to provide an image url when adding a player  return
 (<br>)image should be player's picture  return
(<br>)updates should not require a refresh to display changes to roster  return

(<br>)Integration tests  return
(<br>)when user uses form to select player, correct player should be recognized  return  return
(<br>)changes should be applied to correct player  return

(<br>)Functonal tests  return
(<br>)as a user, I should be able to utilize the forms to make changes to roster  return
(<br>)all changes should update as they are made without a refresh  return

(<br>)Acceptance test  return
(<br>)user can use the forms to make changes to roster  return



