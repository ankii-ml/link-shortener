# link-shortener

## Link Shortener Service

## Overview
A URL shortening service built with pure Node.js HTTP, featuring Base62 encoding for short codes and click analytics. This project emphasizes a dependency-free approach for core functionality.

## Features
*   **Base62 Encoding**: Generates short URLs using a Base62 encoding scheme for efficient and compact codes.
*   **Click Analytics**: Tracks and records clicks for each shortened URL.
*   **Zero Dependencies**: Implemented without external packages, relying solely on Node.js built-in HTTP modules.

## Tech Stack
*   ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
*   ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
*   REST APIs
*   System Design

## Verified Setup
1.  **Clone the repository**: `git clone [repository-url]`
2.  **Navigate to the project directory**: `cd link-shortener`
3.  **Install dependencies**: `npm install` (Note: While the core shortener is dependency-free, `package.json` may contain dev dependencies for testing).
4.  **Run the application**: `node server.js`

## Usage
Once the server is running, you can interact with the API to shorten URLs and retrieve click analytics. Specific endpoints for shortening and redirection are available.

## Project Structure
link-shortener/
├── server.js             # Main application server
├── shortener.js          # Core URL shortening logic (Base62 encoding, analytics)
├── package.json          # Project metadata and scripts
└── test/
    └── shortener.test.js # Unit tests for the shortener module

## Interview Questions
1.  How does the Base62 encoding contribute to the efficiency and uniqueness of the shortened URLs in this project?
2.  Describe the implementation of click analytics. What data structures or mechanisms would you use to store and retrieve click counts efficiently in a production environment?
3.  Given the
