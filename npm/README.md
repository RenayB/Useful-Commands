# Npm Pacakge Commands 

- `npm init`
	: Initializes the package.json file of a project

- `npm install`
	: Installs the dependencies listed in package.json

- `npm install <package>`
	: Installs a package from the npm registry

- `npm install -g <package>`
	: Installs a package globally on your machine

- ` npm uninstall <package>`
	: uninstalls packages that are already installed

- `npm uninstall -g <package>`
	: Uninstalls a global package from your machine

- `npm update <package>`
	: Updates the specified package to the latest version available. If 'package' is not specified, it updates every package

- `npm update -g <package>`
	: Updates a global package to the latest version available

- `npm list`
	: Lists all the installed packages and their versions, along with their dependencies in a tree structure

- `npm view <package> <version>`
	: Shows available details about the specified package. If the version is not set, it defaults to the latest version

- `npm run <script>`
	: Executes the specified 'script', if found as a property of the 'script' object in package.json

- `npm help <term>`
	: Tries to show the appropriate documentation page for the term provided 

- `npm audit`
	: it detects all security vulnerabilities in the dependencies which could be exploited by a hacker

## React Related

- `npm install serve -g`
	: Installs *serve* , a lightweight web server. It serves static site and single page application.

- `serve ./index.html`
	: Runs single html file to the following path http://localhost:5000

- `npm install -g create-react-app`
	:  creates single page React application skeleton