
# Paste-App
The Paste App is a web application that allows users to manage and share their text-based pastes. The app provides a simple, intuitive interface to create, view, and organize paste entries. Built with React, Redux, and Tailwind CSS, the app aims to offer a clean and efficient user experience.

# Features
Create and manage pastes: Users can create new pastes and save them.

View pastes: Users can view pastes that they have created.

Paste management: CRUD (Create, Read, Update, Delete) functionality to manage your pastes.

Responsive design: Built with Tailwind CSS, ensuring a smooth experience on mobile and desktop devices.

# Tech Stack
React: For building the user interface and managing components.

Redux: For state management across the application.

Tailwind CSS: For utility-first CSS, making it easy to design responsive layouts.

Vite: Used as the build tool for faster development and production builds.

ESLint: For linting JavaScript and ensuring code quality.

# File Structure
src/: Contains all the source code for the app.

components/: Reusable React components like Home, Navbar, Paste, and ViewPaste.

redux/: Contains Redux state management files (pasteSlice.js, store.js).

data/: Stores static data, such as Navbar.js for navigation data.

utlis/: Utility functions like formatDate.js.

App.jsx: The root component that renders the app.

main.jsx: Entry point of the app, responsible for rendering the App component to the DOM.

index.css: Global styles for the app.
