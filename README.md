# Hanzlu Project (Common Repository)

This repository is the common container for the **Hanzlu Project**. It links to two separate repositories for the **client** and **server** as Git submodules.

## Project Structure

- `client/` – Contains the front-end React application for the Hanzlu project.
- `server/` – Contains the back-end Node Express server for the Hanzlu project.

### Submodules

This repository uses Git **submodules** to manage the **client** and **server** code separately. This allows you to work on and deploy the client and server independently while keeping them organized within a single common repository.

- **Client Repository**: [Hanzlu Project Client](https://github.com/ashikibrahim07/hanzlu-project-client)
- **Server Repository**: [Hanzlu Project Server](https://github.com/ashikibrahim07/hanzlu-project-server)

## Setup

To get started with this repository, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/ashikibrahim07/hanzlu-project-mern.git
   cd hanzlu-project-mern
   ```

2. Initialize and update the submodules:

   ```bash
   git submodule init
   git submodule update
   ```

   This will clone the **client** and **server** repositories into the `client/` and `server/` directories.

## Development

### Client

The **client** is a React application built using the latest front-end technologies like React, Tailwind CSS, and Redux. You can develop and run it independently:

1. Navigate to the `client/` directory:

   ```bash
   cd client
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

### Server

The **server** is a Node.js and Express backend that handles the business logic and API calls. You can develop and run it independently:

1. Navigate to the `server/` directory:

   ```bash
   cd server
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   npm start
   ```

## Contributions

Feel free to fork the repository and submit pull requests if you would like to contribute. We welcome improvements and fixes!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
