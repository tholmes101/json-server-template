# Zoo Animals App

## Description

This project is designed to display pictures of zoo animals. 
It also has a form so that you can add animals to the list, 
add some likes to a particular animal, and delete an animal from the list.

## Setup

When you're ready to start building your project, run:

```sh
npm install
```
Install JSON Server globally on your machine:

```sh
npm install -g json-server
```
You can use the following commands to run the application:

- `json-server --watch db.json`: run the backend on [http://localhost:3000](http://localhost:3000)
- `explorer.exe index.html`: to open the browser on the frontend

## Running the Server Locally

To run your server in development mode, run:

```sh
npm run dev
```

While running in development mode, the server will re-load any time you make
changes to the `db.json` file, so you can test our your seed data.

While your server is running, you can make requests to
[http://localhost:3000](http://localhost:3000). Check it out in the browser to
make sure your server works!
