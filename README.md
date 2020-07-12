<br />

<p align="center">
  <img alt="Logo" src="./.github/logo.png" width="130px" />
</p>

<h1 align="center" style="text-align: center;">GoFinances</h1>

<p align="center">
	<a href="https://github.com/LuizFerK">
		<img alt="Author" src="https://img.shields.io/badge/author-Luiz%20Fernando-FF872C?style=flat" />
	</a>
	<a href="#">
		<img alt="Languages" src="https://img.shields.io/github/languages/count/LuizFerK/GoFinances?color=%23FF872C&style=flat-" />
	</a>
	<a href="hhttps://github.com/LuizFerK/GoFinances/stargazers">
		<img alt="Stars" src="https://img.shields.io/github/stars/LuizFerK/GoFinances?color=FF872C&style=flat" />
	</a>
	<a href="https://github.com/LuizFerK/GoFinances/network/members">
		<img alt="Forks" src="https://img.shields.io/github/forks/LuizFerK/GoFinances?color=%23FF872C&style=flat" />
	</a>
	<a href="https://github.com/LuizFerK/GoFinances/graphs/contributors">
		<img alt="Contributors" src="https://img.shields.io/github/contributors/LuizFerK/GoFinances?color=FF872C&style=flat" />
	</a>
</p>

<p align="center">
	<b>Help yourself to controll your daily transactions and save money!</b><br />
	<span>Created with Node.js, ReactJS, all with Typescript.</span><br />
	<sub>Made with ❤️</sub>
</p>

<br />

<img alt="Dashboard" src="./.github/dashboard.png" />
<img alt="DashboardList" src="./.github/dashboardlist.png" />
<img alt="Import" src="./.github/import.png" />

<br />

# :pushpin: Contents

- [Features](#rocket-features)
- [Installation](#wrench-installation)
- [Getting started](#bulb-getting-started)
- [Techs](#fire-techs)
- [Issues](#bug-issues)
- [License](#book-license)

# :rocket: Features

- Create income and outcome transactions manually
- Create transactions through the import of a .csv document
- See all your transaction history
- See all your loss and profit to control your money and save it!

# :wrench: Installation

### Required :warning:
- Yarn
- Node.js
- Postgres

### SSH

SSH URLs provide access to a Git repository via SSH, a secure protocol. If you have an SSH key registered in your GitHub account, clone the project using this command:

```git clone git@github.com:LuizFerK/GoFinances.git```

### HTTPS

In case you don't have an SSH key on your GitHub account, you can clone the project using the HTTPS URL, run this command:

```git clone https://github.com/LuizFerK/GoFinances.git```

**Both of this commands will generates a folder called GoFinances, with all the project**

# :bulb: Getting started

### Server

1. Open the **server** folder and run ```yarn``` to install the dependencies;
2. Rename the ```ormconfig.example.json``` to ```ormconfig.json``` and add your postgres **port**, **user** and **password** in the archive;
3. Create a database named ```gofinances``` on your postgres;
4. Run ```yarn typeorm migration:run``` to run the migrations to your database;
5. If all goes well, run ```yarn dev:server``` to open the development server on port 3333.

### Web

1. Open the **web** folder an run ```yarn``` to install the dependencies;
2. Run ```yarn start``` to open the web application on port 3000. (the app will open in your browser automatically)

# :fire: Techs

### Typescript (language)

### Node.js (server)
- Express
- TypeORM
- Multer
- CORS

### ReactJS (web)
- Axios
- Styled Components
- React Router DOM
- React Dropzone

# :bug: Issues

Find a bug or error on the project? Please, feel free to send me the issue on the [GoFinances issues area](https://github.com/LuizFerK/GoFinances/issues), with a title and a description of your found!

If you know the origin of the error and know how to resolve it, please, send me a pull request, I will love to review it!

# :book: License

Released in 2020.

This project is under the [MIT license](https://github.com/LuizFerK/GoFinances/blob/master/LICENSE).

<p align="center">
	< keep coding /> :rocket: :heart:
</p>
