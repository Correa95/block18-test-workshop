# block18-test-workshop

#Unit Tests

# Unit Tests 1: A function called "Multiplication"

# Happy Path

--The functions should take two parameters, x and y.
--x and y can either be an integer (whole number) or a decimal.
--The output should be the mutliplication of x and y (x , y).

# Unhappy Path

--function doesnt multiply x and y.
--output is a undefine, string, NaN.
--output gave two numbers instead of one.
--no argument pass when calling the function.

# Unit Tests 2: A function called "concatOdds" that takes two arrays as parameter and returns single array containing only odd numbers.

# Happy Path

--The function parameter are from the given arrays and return an array of odd numbers.
--the function should be able to filter through any given arrays.
--The function should contain an if statment to check if the given array is divisible % or not  
--if it does not use the push method to push it the new array of odds numbers
--the functon should filter out duplicated numbers in the newly created array
--The function should use the sort method to sort the new array.

# Unhappy Path

--No output is given in the new array.
--The filter method did not work and all numbers get pushed into new array.
--duplicated numbers are outputed in the new array.

# A shopping cart checkout feature that allows the user to be a guest or sign in with an account. Should be prompted to sign in or create an account but isnt required to checkout.

# Happy Path

--The user is ask to "sign in", "create an account", or "continue as a guest" when selecting checkout.
--If user signs in the cart program should show past orders or "suggested items" based off past purchase orders.
--Cart program should save the users past purchases when signed in or save current cart after creating an account and checking out.
--If the user signs in the cart program should have saved past information for faster checkout (payment, address, etc.).

# Unhappy Path

--application takes user to checkout after hitting "Log In" with no information.
--previous user items still in cart.
--shopping cart doesnt show a list of added items.
--application doesnt save past purchase history of users.
--application does not validate users log in information.
