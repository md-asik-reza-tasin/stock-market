# Full-Stack Application Using Python and React.js

This project is an application built with Python for the backend and React.js for the frontend. It allows users to view, add, update, and delete data. The backend uses Flask to manage the data, and the frontend provides an interactive interface to display the information. The app uses an SQLite database to store the data.

The main goal of this project is to provide a simple yet powerful tool for managing information and to showcase the use of Python and React.js in a full-stack web application.

### Live:
You can access the live version of the app here: [Live Demo](https://stock-market-1-29wp.onrender.com/)

### Branches:
- **main**:  
  The initial setup of the project. In this branch, I install all the necessary dependencies for both the backend (Flask) and frontend (React.js), setting up the foundation for the project.
  
- **jsonModel**:  
  Focuses on showing data using the frontend as much as possible. The backend is used to create APIs for fetching data (GET requests), while the frontend handles the display and interaction of the data.
  
- **sqlModel**:  
  This branch contains the full implementation of the project, where the backend (Flask) uses SQLite for data storage. It includes all the features such as adding, updating, and deleting data, along with handling complex queries to manage and display data efficiently.

### What You Can Do in the Web App:
- **View Data**: You can choose a trade code and view the data related to that specific trade code.
- **Add New Data**: Add a new stock or select an existing trade code to complete the form and submit it to the application.
- **Update or Delete Data**: You can edit existing stock data or delete it if it's no longer needed.
- **View Charts**: See the chart showing stock volume and closing values to understand trends.
- **Search by Date**: Filter and search for stock data by specifying a date range to view specific information.

### Challenging Parts:
- **Handling Database Connections**: Managing database connections and ensuring data is properly stored and retrieved was tricky at first.
- **Integrating Backend and Frontend**: Connecting the backend (Flask) with the frontend (React.js) to fetch and display data smoothly was a challenge.
- **Chart Implementation**: Setting up charts to visualize stock data based on volume and close values took some time to understand and implement correctly.

### What I Learned:
- **Flask and SQLite**: I learned how to use Flask for creating APIs and SQLite for managing data storage in a web app.
- **React.js**: I learned how to build interactive user interfaces with React.js and connect it to a backend.
- **Data Visualization**: I learned how to display data on charts, making it easier to understand trends and patterns.
