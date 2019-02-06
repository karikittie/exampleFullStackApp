# Example Full-Stack App

### Server
The server is written in node.js using the express framework.
The best place to start is the package.json where you can find
all of the libraries being used in the project as well as the
various scripts you can run.

### Client
The client is written in React using the create-react-app
command line application. This gives us a significant amount of
boilerplate code.

### Setting up the project
After pulling down the project, you'll need to install a node
version greater than or equal to 10.11.0. You'll also need to
install yarn globally using the command `npm install -g yarn`.
Once node and yarn are both installed, you'll need to install
all of the project dependencies using `yarn install`.

### Starting the project
There are 3 commands you can use, depending on what you're
developing:
`yarn start-server` will start the back-end app for development.
`yarn start-client` will start the react app for development.
`yarn start-dev` will start both the server and client.
All of the commands will watch the files and reload the server
and/or client if something is updated.