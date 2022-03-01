# ![image](./public/img/favicon.png) Chat App

## Table of Contents

- [Demo](#demo)
- [Description](#description)
- [Features](#features)
- [Concepts Used](#concepts-used)
- [Run Locally](#run-locally)
- [Tech Stack](#tech-stack)
- [Author](#author)

## Demo

[Chat App](https://satvik-chat-app.herokuapp.com/)

![Demo video](./demo/chat-app-demo.gif)

## Description

This is a basic chat app that allows users to chat with each other if they are in the same room. I have developed this app through Node.JS and Socket.IO on the backend and HTML, CSS and client side JavaScript on the frontend.

## Features

In this app, users need to enter their name and room name to join the chat. This is done through a form. Users can then send messages to other users in the same room as well as share their current location which is achieved through the use of [geo-location API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API).

It also maintains a list of the users in a particular room and prohibits users with the same name to enter the same room.

It also has a feature that does not allow an user to send profane messages.

## Concepts Used

- Socket.IO
- Events
- Promises
- Building dynamic web pages
- Asynchronous Node.JS
- Server side programming through Express.JS

## Run Locally

Clone the project

```bash
  git clone https://github.com/satviksriv/chat-app.git
```

Go to the project directory

```bash
  cd chat-app
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

## Tech Stack

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## Author

- [@satviksriv](https://github.com/satviksriv)
