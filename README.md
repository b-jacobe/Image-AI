# Image-AI

## Image Generator Using DALL·E API

![OpenAI](https://img.shields.io/badge/OpenAI-DALL·E-blue)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=flat-square&logo=vite&logoColor=FFD62E)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

![image info](./img/dream.png)

This repository hosts an application that allows users to generate images from text prompts using OpenAI's DALL·E API. It features a user-friendly interface for both the initiation of image generation and the display of resulting artwork.

## Features

- Generate images through text prompts.
- User-friendly frontend interface.
- Backend integration with OpenAI's DALL·E API.

## Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed to handle package management and server operations. You will also need an OpenAI account, a token within a .env file to run this properly.

## Installation

Clone the repository:

```bash
git clone git@github.com:b-jacobe/Image-AI.git
cd Image-AI
```

Install dependencies:

```bash
npm install
```

## Running the Application

To run the front end locally:

```bash
npm run dev
```

This will start the Vite development server and load the frontend on http://localhost:[yourport#]

To run the backend server:

```bash
node server.js
```

The backend will start and listen for requests to perform API calls to OpenAI.

## Usage

Once both servers are running, navigate to http://localhost:[yourport#] on your browser to use the application. Enter your desired prompt and generate images.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
