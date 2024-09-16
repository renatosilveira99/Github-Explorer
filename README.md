# Github Explorer

**Github Explorer** is a web application developed in **React.js** during the GoStack Bootcamp by [Rocketseat](https://rocketseat.com.br). The app integrates with the public GitHub API, allowing users to search for repositories, save them locally, and view all the issues related to the repository.

<img src="./dashboard.png" alt="Dashboard" width="500"/>
<img src="./repo.png" alt="Repository Issues" width="500"/>

## Features

- **Repository Search**: Search for repositories on GitHub by name.
- **Repository Listing**: View saved repositories with details like stars, forks, and open issues.
- **Issue Listing**: Display all issues for each repository.
- **API Integration**: Fetch data directly from GitHub's public API.

## Technologies Used

- **React.js**: JavaScript library for building user interfaces.
- **Axios**: HTTP client for API requests.
- **Styled-components**: For styling components in a modular way.
- **React Router**: Navigation between application pages.

## Installation

To set up and run the application locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/renatosilveira99/github-explorer
   cd github-explorer
   ```

2. **Install dependencies:**

   If you are using Yarn, run:

   ```bash
   yarn
   ```

   Or, if you are using npm, run:

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   yarn start
   ```

   Or, if using npm:

   ```bash
   npm start
   ```

4. The app will be running at `http://localhost:3000`.

## Project Structure

- **src/**: Contains the main code of the application.
  - **pages/**: Includes the Dashboard and Repository pages.
  - **services/**: Contains the Axios instance to connect with the GitHub API.
  - **styles/**: Global styles and styled-components.
  
## Screenshots

- **Dashboard**: Search and view a list of saved repositories.
- **Repository Details**: View details and issues for each repository.
