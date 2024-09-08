To run this project :

Please install VITE globally or in the project folder:


Install Vite: If Vite is not installed in your project, you can install it by running:

**npm install vite --save-dev**
This will install Vite as a development dependency.

Ensure Node Modules Are Installed: If you haven’t run npm install in the project directory yet, do so to install all dependencies listed in package.json:

**npm install**
Check package.json Scripts: Ensure that the dev script in your package.json correctly references Vite. It should look something like this:

json
Copy code
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "serve": "vite preview"
}


Global Installation: If you want to use Vite globally across multiple projects, you can install it globally:

**npm install -g vite**
