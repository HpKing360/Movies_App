<div align="center" >

  <br/>
  <br/>
  <img src="/public/logo-dark.png#gh-dark-mode-only" alt="logo" width="200" height="auto" />
  <img src="/public/logo-light.png#gh-light-mode-only" alt="logo" width="200" height="auto" />
  <br/>
  <br/>

  <p >
HpMovies is a simple movie application built with React JS, Typescript, and Tailwind CSS, <br/> which allows users to search and view the trailer of both movies and TV series.
  </p>

<p>
  <a href="https://github.com/HpKing360/Movies_App/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/HpKing360/Movies_App" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/HpKing360/Movies_App" alt="last update" />
  </a>
  <a href="https://github.com/HpKing360/Movies_App/network/members">
    <img src="https://img.shields.io/github/forks/HpKing360/Movies_App" alt="forks" />
  </a>
  <a href="https://github.com/HpKing360/Movies_App/stargazers">
    <img src="https://img.shields.io/github/stars/HpKing360/Movies_App" alt="stars" />
  </a>
  <a href="https://github.com/HpKing360/Movies_App/issues/">
    <img src="https://img.shields.io/github/issues/HpKing360/Movies_App" alt="open issues" />
  </a>
  <a href="https://github.com/HpKing360/Movies_App/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/HpKing360/Movies_App.svg" alt="license" />
  </a>
</p>
   
</div>

## Features

1. **Search Movies and TV Series:**

   1. Users can easily search for their favorite movies and TV series within the application.
   2. View trailers to get a sneak peek before watching.

2. **Detailed Movie Information:**

   1. Access comprehensive information about a selected movie, including details about the cast, crew, and more.

<br/>


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

\***\* Prerequisites \*\***

- git
  If you want to clone the project from GitHub and work with it locally, you will need to have Git installed on your system. You can download and install Git from the official website (**[https://git-scm.com/](https://git-scm.com/)**).
- Node.js
  Application requires Node.js to be installed on your system in order to run. You can download and install the latest version of Node.js from the official website (**[https://nodejs.org/](https://nodejs.org/)**).
- npm (Node Package Manager)
  npm is the package manager for Node.js, and is used to manage the dependencies and packages required for your Next.js project. It is installed automatically when you install Node.js.
  To check if npm is installed on your system, you can open a terminal or command prompt and enter the following command:
  ```bash
  npm -v
  ```

Once you have these prerequisites in place, you can proceed to clone the project from GitHub using Git.

<br/>

\***\* Installing \*\***

Make sure you have all the necessary prerequisites installed on your system. Follow the below steps to install the setup the project on your machine:

- Open a terminal or command prompt and navigate to the directory where you want to clone the project.
- Run the following command to clone the project from GitHub:
  ```bash
  git clone https://github.com/HpKing360/Movies_App.git
  ```
- This will create a new directory called "movie-app" in the current location, containing the code for the movie app project.
- Navigate to the project directory by running the following command:

  ```bash
  cd Movies_App
  ```

- Run the following command to install the project's dependencies using npm:

  ```bash
  npm install
  ```

- Start the server

  ```bash
  npm run dev
  ```

- To use the movie project, you will need to set up some environment variables on your development machine. Here are the steps to follow:

  1. Create a **`.env`** file in the root of the project.
  2. Add the following variables to the **`.env`** file, replacing the placeholder values with your own:

  ```jsx
  VITE_API_KEY=<your-tmdb-api-key>
  VITE_TMDB_API_BASE_URL = https://api.themoviedb.org/3
  ```

  3. Save the **`.env`** file.

- Once the dependencies are installed, you can run the project locally by running the following command:
  ```bash
  npm run dev
  ```

This will start the development server and open the movie application in your default web browser.

<br/>

## Contributing

We welcome contributions to movie app! If you have an idea for a new feature, an improvement to an existing feature, or a bug fix, please open an issue to discuss it before submitting a pull request. This helps me to review and understand your changes more efficiently.

To contribute code to movie app project:

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Commit your changes to the new branch
4. Run the automated tests to ensure that your changes do not break any existing functionality
5. Open a pull request back to the main repository, including a description of your changes and any relevant issue numbers

Thank you for your contribution to Movie app project! We appreciate your efforts to help make this a great movie application.

<br/>

## Credits

UI/UX design adapted from Tuat Tran Anh's tutorial.

- Tutorial: [Responsive React Movies App With API | ReactJS Movies | ReactJS Tutorial](https://youtu.be/ntYXj9W1Ez8?si=ddwD3FZ6sot_NX9K)
