# 0x06-StarWars API

## Overview

The “0. Star Wars Characters” project involves interacting with an external API to fetch and display information about Star Wars characters based on the movie ID provided as an argument. This script prints all characters of a Star Wars movie.

## Concepts Needed

To successfully complete this project, you need to be familiar with the following key concepts related to web programming, API interaction, and asynchronous programming in JavaScript:

- **HTTP Requests in JavaScript**: Understanding how to make HTTP requests to external services using the `request` module or alternatives like `fetch` in Node.js.

- **Working with APIs**: Understanding the basics of RESTful APIs and how to interact with them, including parsing JSON data returned by APIs.

- **Asynchronous Programming**: Managing asynchronous operations with callbacks, promises, and `async/await` syntax, and handling API response data asynchronously.

- **Command Line Arguments in Node.js**: Using the `process.argv` array to access command-line arguments passed to a Node.js script.

- **Array Manipulation and Iteration**: Iterating over arrays and manipulating data structures to format and display character names.

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 20.04 LTS using Node.js (version 10.14.x)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/node`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should be semistandard compliant. Rules of Standard + semicolons on top. Also as reference: AirBnB style
- All your files must be executable
- The length of your files will be tested using `wc`
- You are not allowed to use `var`

## Additional Resources

- [Mock Technical Interview](https://www.mockinterview.co/)
- [Semi-Standard Documentation](https://github.com/standard/semistandard)
- [Request Module Documentation](https://www.npmjs.com/package/request)

## Installation and Usage

1. **Install Node.js 10**:
   ```sh
   $ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
   $ sudo apt-get install -y nodejs

