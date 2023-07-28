# React Redux Project with  Users, Albums, and Photos

This project is a React-Redux application that showcases fake users, albums, and photos. It utilizes `redux-toolkit`, `faker` for generating fake names, `classNames` for styling, and `Tailwind CSS` for additional styling.

## Features

- Display a list of fake users with their names and other details.
- Each user has albums, and each album has a collection of photos.
- Add new users and albums to the list.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine.
2. Open the project directory in your terminal.
3. Install the required dependencies using npm:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

This will run the project in development mode and open it in your default web browser at `http://localhost:3000`.

## Dependencies

This project relies on the following npm packages:

- `react`: JavaScript library for building user interfaces.
- `redux`: Predictable state container for managing application state.
- `react-redux`: Official React bindings for Redux to use with React components.
- `redux-toolkit`: Utility library that simplifies the usage of Redux with some additional features.
- `faker`: Library for generating fake data, used for creating fake user names.
- `classnames`: Utility for joining CSS class names together, used for conditional styling.
- `tailwindcss`: Utility-first CSS framework used for styling components.

## Project Structure

```
src
|-- components
|   |-- Button.js
|   |-- Panel.js
|   |-- Skeleton.js
|   |-- AddUserForm.js
|   |-- UsersList.js
|-- store
|   |-- slices
|   |   |-- usersSlice.js
|   |-- thunks
|   |   |-- addUser.js
|   |   |-- fetchUsers.js
|   | -- index.js
|   |-- photos
|   |   |-- photosSlice.js
|   |   |-- photosData.js
|-- App.js
|-- index.js
```

## How to Use

The application will start by displaying a list of fake users with their names and other details. You can click on each user to see their albums and click on each album to view its photos.

To add a new user, click on the "Add User" button and fill in the required details in the form. The new user will be added to the list.

To add a new album to a user, click on the "Add Album" button on the user's card and fill in the required details in the form. The new album will be added to the user's albums.

## Contributions

Contributions to this project are welcome! If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify it as per your requirements.

---

Thank you for using our React-Redux project! We hope you find it helpful and enjoyable to use. If you have any questions or need further assistance, please don't hesitate to reach out. Happy coding!