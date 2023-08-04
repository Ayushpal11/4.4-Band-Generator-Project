# Anime-Name-Genrator

## Overview

The Anime Name Generator is a simple web application built with Node.js and Express.js that generates random anime names. 
Users can visit the web page and click the "Generate Name" button to get a random anime name.
If no name has been generated yet, a welcome message is displayed.

## Table of Contents

- [Dependencies](#dependencies)
- [Contributions](#contributions)
- [How it Works](#how-it-works)
- [Author](#author)

## Dependencies

The application uses the following Node.js packages:

- [express](https://www.npmjs.com/package/express): A fast, minimalist web framework for Node.js.
- [body-parser](https://www.npmjs.com/package/body-parser): Node.js body parsing middleware to handle form data.

## How it Works

- The application sets up an Express.js server on port 3000.

- When a user accesses the main page (`/`), the server renders the `index.ejs` template and passes the `randomname` variable to the template.

- If the user clicks on the "Generate Name" button, a POST request is sent to the server's `/submit` route.

- The server generates a random anime name from a predefined list of names and stores it in the `randomname` variable.

- The server then redirects the user back to the main page (`/`), where the generated anime name will be displayed.

## Contributions

Contributions to this project are welcome. If you find any issues or have ideas for improvements, feel free to open an issue or submit a pull request on GitHub.

## Author

This Anime Name Generator was created by Ayush Pal(https://github.com/Ayushpal11).
