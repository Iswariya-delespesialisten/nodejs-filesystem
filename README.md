# Nodejs- Filesystem

A Node.js application that provides a simple file management system with RESTful API endpoints. Users can create timestamped text files and retrieve a list of existing text files stored in the "Output" directory. The API is documented for easy integration and usage.

## API Deployment

The deployed Website: https://nodejs-filesystem-3xc8.onrender.com

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.



## Usage

POST: Create Text File
http://localhost:3000/createTextFile

1. Send the Request:

- After configuring the request, click the "Send" button to send the POST request to the specified URL.

2. Response:

- You will receive a response from the server, which may indicate whether the file creation was successful or not. Be sure to handle the response accordingly in your application.

GET: List Text Files
http://localhost:3000/getTextFiles

1. Send the Request:

- After configuring the request, click the "Send" button to send the GET request to the specified URL.

2. Response:

- You will receive a response from the server containing the list of text files created using the previous POST requests. The server's response the file names of text files.
- You can view the list of text files in the Postman response panel.





## License

This project is licensed under the [License Name] License - see the LICENSE file for details.
