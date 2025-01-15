Overview

This project is a real-time multiplayer chess application built using TypeScript, React, and WebSockets. The application allows two players to connect, play chess, and receive live updates of the game state.

Features

Real-time two-player chess game.

WebSocket communication for seamless synchronization.

Intuitive and interactive UI built with React.

TypeScript for type safety and improved code quality.

Technologies Used

React: Front-end library for building user interfaces.

TypeScript: Adds static typing to JavaScript, improving code maintainability.

WebSocket: Enables real-time, bidirectional communication between clients.

tailwind : For styling the application.


WebSocket Communication

The application uses WebSocket for real-time communication between players. Here's a brief overview of the WebSocket protocol in this project:

Server-Side

The WebSocket server listens for player connections.

It handles messages such as:

Player move: When a player makes a move, the server broadcasts the move to the other player.

Game state update: Keeps both players' game states synchronized.

Client-Side

A WebSocket connection is established when the app loads.

The client sends and receives messages related to:

Player moves

Game status (e.g., checkmate, stalemate)
