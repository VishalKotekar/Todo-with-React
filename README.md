# Todo Project

This is a simple Todo application built with React, Vite, and styled with Tailwind CSS. It uses the Context API for state management and LocalStorage to persist data across sessions.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add, edit, and delete todos
- Mark todos as completed
- Persistent storage using LocalStorage
- Responsive design with Tailwind CSS
- Context API for state management

## Tech Stack

- **React**: Frontend library for building user interfaces
- **Vite**: Build tool that provides a fast development environment
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Context API**: For state management across components
- **LocalStorage**: For persisting todos in the browser

## Getting Started

To get started with the project, follow these steps:

### Prerequisites

Make sure you have the following installed:

- Node.js (version 12 or higher)
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/VishalKotekar/Todo-with-React.git
   cd todo-project
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:3000` (or the port specified in your terminal).

## Usage

Once the application is running, you can:

- Add a new todo by typing in the input field and pressing the "Add Todo" button.
- Edit a todo by clicking on it.
- Delete a todo by clicking the trash icon next to it.
- Toggle the completed state of a todo by clicking the checkbox.

Todos are saved in LocalStorage, so they will persist even after you refresh the page.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
