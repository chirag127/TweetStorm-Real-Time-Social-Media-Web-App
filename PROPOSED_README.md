# TweetStorm-Real-Time-Social-Media-Web-App

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/TweetStorm-Real-Time-Social-Media-Web-App/ci.yml?branch=main&style=flat-square)](https://github.com/chirag127/TweetStorm-Real-Time-Social-Media-Web-App/actions/workflows/ci.yml)
[![License](https://img.shields.io/github/license/chirag127/TweetStorm-Real-Time-Social-Media-Web-App?style=flat-square)](https://github.com/chirag127/TweetStorm-Real-Time-Social-Media-Web-App/blob/main/LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://www.javascript.com/)
[![Stars](https://img.shields.io/github/stars/chirag127/TweetStorm-Real-Time-Social-Media-Web-App?style=flat-square)](https://github.com/chirag127/TweetStorm-Real-Time-Social-Media-Web-App/stargazers)

A full-stack web application replicating core Twitter functionalities, providing real-time tweeting, user profiles, and social feeds.

Star ⭐ this repo!

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [AI Agent Directives](#ai-agent-directives)

## Overview

TweetStorm is a web application built using modern JavaScript technologies to emulate the core features of Twitter. It enables users to post real-time tweets, create profiles, follow other users, and view social feeds. This project serves as a practical demonstration of full-stack development with a focus on real-time data handling and user experience.

## Features

- **Real-time Tweeting:** Post and view tweets in real-time.
- **User Profiles:** Create and customize user profiles.
- **Social Feeds:** View a feed of tweets from followed users.
- **Modern JavaScript:** Utilizes the latest JavaScript features and frameworks.
- **Full-Stack Development:** Covers both front-end and back-end aspects of web development.

## Architecture


├── client/                 # Front-end code
│   ├── public/           # Static assets
│   ├── src/              # Source code
│   │   ├── components/   # React components
│   │   ├── App.js        # Main application component
│   │   └── index.js      # Entry point
│   ├── package.json      # Dependencies and scripts
│   └── webpack.config.js # Configuration for webpack
├── server/                 # Back-end code
│   ├── models/           # Data models
│   ├── routes/           # API routes
│   ├── app.js            # Main server application
│   └── package.json      # Dependencies and scripts
├── .gitignore            # Specifies intentionally untracked files that Git should ignore
├── LICENSE               # License information
└── README.md             # Project documentation


## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)
- MongoDB (for database)

### Installation

1. Clone the repository:
   sh
   git clone https://github.com/chirag127/TweetStorm-Real-Time-Social-Media-Web-App.git
   cd TweetStorm-Real-Time-Social-Media-Web-App
   

2. Install server dependencies:
   sh
   cd server
   npm install
   

3. Install client dependencies:
   sh
   cd client
   npm install
   

4. Configure MongoDB:
   - Ensure MongoDB is installed and running.
   - Update the connection string in `server/app.js`.

## Usage

1. Start the server:
   sh
   cd server
   npm start
   

2. Start the client:
   sh
   cd client
   npm start
   

3. Open your browser and navigate to `http://localhost:3000`.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](https://github.com/chirag127/TweetStorm-Real-Time-Social-Media-Web-App/blob/main/.github/CONTRIBUTING.md) file for guidelines on how to contribute.

## License

This project is licensed under the [CC BY-NC](https://github.com/chirag127/TweetStorm-Real-Time-Social-Media-Web-App/blob/main/LICENSE) license.

<details>
<summary>🤖 AI Agent Directives</summary>

yaml
name: TweetStorm-Real-Time-Social-Media-Web-App
description: A full-stack web application replicating core Twitter functionalities, providing real-time tweeting, user profiles, and social feeds.

tech_stack:
  language: JavaScript
  framework: React.js, Node.js
  database: MongoDB
  tooling:
    - npm
    - webpack

architectural_patterns:
  - Full-Stack Development
  - Real-time Data Handling
  - MVC (Model-View-Controller)

principles:
  - SOLID
  - DRY (Don't Repeat Yourself)
  - YAGNI (You Aren't Gonna Need It)

verification_commands:
  lint:
    - command: "npm run lint"
    description: "Run linter to check code quality."
  test:
    - command: "npm run test"
    description: "Run unit tests to ensure code correctness."
  build:
    - command: "npm run build"
    description: "Build the application for deployment."


</details>