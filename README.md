# my-ic-site

A decentralized web application built on the Internet Computer (IC) platform, leveraging a modern frontend and backend framework for scalability, security, and ease of use.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Features
- **Decentralized hosting** on the Internet Computer
- **Frontend**: Vue.js for a responsive and dynamic user interface
- **Backend**: Built with Motoko to interact with IC canisters
- **API Integration**: Seamlessly communicates between frontend and backend

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)
- [DFINITY SDK](https://internetcomputer.org/docs/current/developer-docs/quickstart/quickstart-intro/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Lidyakano/my-ic-site.git
   cd my-ic-site
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage
1. Start the Internet Computer locally:
   ```bash
   dfx start
   ```
2. Deploy the backend canisters:
   ```bash
   dfx deploy
   ```
3. Run the frontend:
   ```bash
   npm run serve
   ```
4. Access the app at `http://localhost:8080`

## Project Structure
- `frontend/` - Vue.js frontend
- `backend/` - Motoko backend logic
- `src/` - Shared assets and configuration files

## License
This project is licensed under the MIT License.
