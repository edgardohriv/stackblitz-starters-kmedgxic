# Angular Starter

This project is an Angular application. Follow these steps to run it on your computer.

## Prerequisites

- [Node.js](https://nodejs.org/) compatible with Angular 19 (Node.js 20 LTS is recommended). npm is included with Node.js.
- Git, if you need to clone the repository.

## Run the application

1. Clone the repository and enter its directory:

	```bash
	git clone https://github.com/edgardohriv/stackblitz-starters-kmedgxic.git
	cd stackblitz-starters-kmedgxic
	```

	If you already have the project files, open a terminal in the project directory instead.

2. Install the dependencies:

	```bash
	npm ci
	```

3. Start the Angular development server:

	```bash
	npm start
	```

4. Open [http://localhost:4200](http://localhost:4200) in your browser. The server watches for code changes and reloads the app.

5. To stop the server, press `Ctrl+C` in the terminal.

## Build for production

To create a production build, run:

```bash
npm run build
```

The build output is written to `dist/`.