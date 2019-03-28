
This exercises requires a student to retrieve a data from the server called studentGrades.json
and display a table that contains the average grade of each student in tabular form.

Write your solution in index.js which is loaded automatically when index.html loads.

The index.html contains a root div element called "grades". You are required to:

1. Fetch the studentGrades.json from the backend using fetch
2. Parse the json data and calculate students average.
3. Display it in tabular form in either table element or div element in the following format

| Student Name | Average Grade |
---|---|
| Bobbee Pohls |   88.44       |
|  ...         |   ...         |

4. Write a unit test for your functions