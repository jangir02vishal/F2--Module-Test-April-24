# Student Portal - Frontend 2 Module Project
This project is a JavaScript and HTML application that imports an array of 100 students and displays their information in a table UI as shown in the provided Figma design.
 
![Screenshot 2024-05-04 130315](https://github.com/jangir02vishal/F2--Module-Test-April-24/assets/136950731/71fe25f0-1f92-4093-bee6-507a3fb72a1e)

## Key Functionalites
- Display all 100 student elements in a table.
* Ensure that the "Name" column includes an image of the student along with their full name (first name + last name).
+ Represent the "passing" attribute as either "passing" or "failed" in the table. If the student is passing (boolean value true), display "passing"; otherwise, display "failed".
- Implement a search bar to filter data based on first name, last name, and email. The search should be case insensitive and can be triggered either on input change or by clicking a search button.
* Create a flex-box layout for buttons with maximum space between them.
+ Implement sorting functionality for the table:
  - Sort A->Z: Ascending order of full name.
  - Sort Z->A: Descending order of full name.
  - Sort by marks: Ascending order of marks.
  - Sort by passing: Show only students who are passing.
  - Sort by class: Ascending order of class.
  - Sort by gender: Display two tables, one containing all female students and the other containing all male students, shown one below the other.
