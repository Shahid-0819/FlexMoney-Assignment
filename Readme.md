
# Yoga Classes Admission Form

This project is a simple admission form for monthly Yoga classes, allowing users to enroll, choose batches, and make monthly payments.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [ER Diagram](#er-diagram)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Deployment](#deployment)
- [Directory Structure](#directory-structure)
- [Built With](#built-with)
- [License](#license)

## Overview

The Yoga Classes Admission Form is a web application built to facilitate the enrollment process for monthly Yoga classes. Users can enroll, choose a batch, and make monthly payments.

## Features

- **Age Limit:** Users within the age range of 18-65 can enroll.
- **Monthly Payment:** Participants pay the fees on a month-to-month basis (500/- Rs INR per month).
- **Batch Selection:** Users can choose a batch from four available slots.
- **Batch Shifting:** Participants can move to any other batch in the following months.

## ER Diagram
![ER Diagram](https://github.com/Shahid-0819/FlexMoney/blob/main/ERDiagram.jpeg)

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- MongoDB

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Shahid-0819/FlexMoney.git
   cd flexmoney/server
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run Server:**

   ```bash
   npm run dev
   ```

4. **Change directory and Install backend dependencies:**

   ```bash
   cd ..
   cd ./backend
   npm i
   nodemon index.js
   ```

## Configuration

Adjust environment variables, database configurations, and any other settings as needed.

## Usage

Start the application and visit [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment

The application is deployed on Netlify

## Directory Structure

```plaintext
flexmoney_assignment/
|-- client/
|   |-- src/
|   |   |-- components/
|   |   |-- utils/
|   |   |-- ...
|   |-- public/
|   |-- package.json
|   |-- README.md
|-- backend/
|   |-- routes/
|   |-- models/
|   |-- config/
|   |-- middleware/
|   |-- controller/
|   |-- utils/
|   |-- index.js
|   |-- package.json
|   |-- README.md
|-- .gitignore
|-- README.md
```

## Built With

- [React.js](https://react.dev/) (Frontend)
- [Express.js](https://expressjs.com/) (Backend)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) (Database)

## License

This project is licensed under the [MIT License](LICENSE).