# Nodejs- Filesystem

A Node.js application that provides a simple file management system with RESTful API endpoints. Users can create timestamped text files and retrieve a list of existing text files stored in the "Output" directory. The API is documented for easy integration and usage.

## API Deployment

The deployed Website: https://nodejs-filesystem-3xc8.onrender.com

### API Request

#### Create the file of current date and time

<h4>End Point: createTextFile</h4>
https://nodejs-filesystem-3xc8.onrender.com/createTextFile

#### Get the files from server

<h4>End Point: getTextFile</h4>
https://nodejs-filesystem-3xc8.onrender.com/getTextFiles

## Last Comitted Hash ID: 2cb84ab12b8761c98d46785c1b0b95ad70715c3a

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

### Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/Shanmugamrskfamily/nodejs-filesystem.git
   ```

2. Navigate to the project directory:

```shell
cd nodejs-filesystem
```

3. Install the dependencies:

```shell
npm install
```

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

## API Documentation

You can find the API documentation for this project https://documenter.getpostman.com/view/28858691/2s9YC7SBXQ

## Contributing

If you'd like to contribute to this project, please follow these guidelines:
Fork the project.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive messages.
Push your changes to your fork.
Submit a pull request to the main branch of the original repository.
Please make sure to update tests as appropriate.

## License

This project is licensed under the [License Name] License - see the LICENSE file for details.
