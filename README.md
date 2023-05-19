# React_User_list
Title: User List App
Description: User List App is a web application developed using the React library. It provides a user interface for viewing, adding, editing, and deleting users in a list.

Functionality:
1. User List Display: The app displays a list of users, including their basic information such as name, surname, email address, and photo.
2. Adding a New User: Users can fill out a form with the necessary information about a new user and add them to the list.
3. Editing a User: The app allows users to modify the information of an existing user, including their name, surname, and email address.
4. Deleting a User: Users can remove a selected user from the list.

Application Structure:
1. App Component: The main component of the application that holds the state of the user list and handles the logic for adding, editing, and deleting users.
2. Users Component: Displays the list of users using the UserItem component for each user.
3. User Component: Displays information about each user, as well as buttons for editing and deleting.
4. UserForms Component: A form for adding a new user, containing fields for entering their name, surname, and email address.

Technical Details:
• The application uses React to build the user interface and manage state.
• User data is loaded from an external data source, using the Axios library for assistance.
