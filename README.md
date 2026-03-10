Question 2 – Fetch Data from API using useEffect
Task
Create a React component that fetches user data from an API and displays it in a list.

API:

https://jsonplaceholder.typicode.com/users

Display:

Name
Email
Example Folder Structure
src/ ├── components/ │ └── Users.jsx ├── App.jsx └── main.jsx

Concepts Covered
useEffect Hook
API Calls (fetch or axios)
useState for storing API data
Logic Explanation
When the component loads, useEffect runs.
An API request is sent to fetch user data.
The received data is stored in state.
The data is displayed using the map() function.
Functionalities
Fetch external data
Dynamically render list of users
Possible Improvements
Add loading state
Add error handling
Move API logic to a separate service file
