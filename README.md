
This project is a simple web application that displays a list of Boston employees, their departments, positions, and salaries. The data is fetched from a `boston.js` file, which contains mock data about employees, and is displayed in a table on the webpage.

 Files:

 1. `index.html`
This is the main HTML file that structures the webpage. It includes the following:
- A title "Boston Employee Data".
- An empty table where employee data will be dynamically added using JavaScript.
- References to two JavaScript files: `boston.js` (for data) and `index.js` (for logic).

 2. `boston.js`
This file contains mock data for Boston employees in JSON format. The data includes:
- `name`: The name of the employee.
- `department`: The department they work in.
- `position`: Their job title.
- `salary`: Their annual salary in USD.

 3. `index.js`
This JavaScript file handles dynamically adding the employee data to the HTML table:
- The data from `boston.js` is loaded and iterated over.
- For each employee, a new row is created in the table with their name, department, position, and salary.
- The salary is formatted with commas (e.g., $75,000).

 How to Run:
1. Clone or download the project files.
2. Open the `index.html` file in any modern web browser.
3. You will see a table with Boston employee data, loaded dynamically from `boston.js`.



 Future Enhancements:
- Add a search or filter functionality for the table.
- Implement sorting by name, department, or salary.
- Retrieve data from an external API instead of a static file.
