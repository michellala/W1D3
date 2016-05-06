# W1D3

Task 1
Insert two additional states into the Hash, but without modifying the initial Hash definition. Instead, add in these new kv pairs after the states object is defined.

Task 2
Declare another hash called cities where the keys are again the state code but the values are arrays of city names.

Add a few (2 to 4) cities for each state.

Task 3
Define a method describe_state that:

Takes as input a state code (eg: 'CA')
Returns the details of that state, including a list of its cities (eg: 'CA is for California. It has 2 major cities: San Francisco, LA')
Tips:

The method should return the string, not output it
Write test code to output the return value to make sure it works, like we have done with previous exercises
Write the code incrementally:
Write the empty method
Write the test code after the method definition, that will actually be doing the puts of the method's return value.
Implement a small part of the method instead of trying to have it return the final string. Eg: 'CA' is for California' only.
Add more functionality and test code
Task 4
Declare another Hash called taxes which is responsible for defining taxes for each of the states (eg: 7.5 for 7.5%). You can just make up the values... though I cannot guarantee that the US Gov't will not come after you for misrepresenting their tax information.

Task 5
Define another method called calculate_tax which:

Takes as input the state code as well as a dollar amount (eg: 123.49)
Determines the tax rate to use based on the provided state
Calculates the tax amount based on that rate
Returns the tax amount rounded to 2 decimal places (eg: 44.53)
Refer to the same tips as Task 3

Task 6
Define a method find_state_for_city which should:

Take as input the name of a city
Return the state code for where that city is located
Of course, for your test code, find states for cities that are actually mentioned in your cities hash


Candidates Exercise 
