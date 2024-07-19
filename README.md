# Demo_UiPath- Challenge 1 Age Calculator
How can you create automation in UiPath that prompts users to input their birth year and then displays their current age?

Solution:
Collect the year of birth using Input dialog activity.
Validate the input is a number and the year is less than or equal to the current year. The validation will avoid providing the negative age.
Write a logic to identify the current age for inputted year of birth.

Note: Handled the exception scenario with proper conditions, valid variable naming convention and analyzed the process before submitting.

Challenge 2
How can you create an automation that creates a list for storing names and displays it.

Solution:
Loop to collect multiple Name dynamically from user using Input Dialog Activity
Use Append Item to Collection activity to store the names in List variable
Convert List to String to Display all the name at once with code

Challenge3
How can you create an automation process of reading a CSV file and displaying its content in the output panel.

Solution:
Use cas operation to read file
Convert Output datatable into string
