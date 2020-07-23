<h3 align="center">
  My Class
</h3>
<h4 align="center">
	🚧  Project in progress...  🚧
</h4>
<p align="center">

  <a href="LICENSE" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>

</p>

# My Class
![MyClass](images/register-teacher-page.png)

# :bookmark_tabs: Index

  - [:clipboard: About](#clipboard-about)
    - [:white_check_mark: Features](#white_check_mark-features)
  - [:computer: Technologies](#computer-technologies)
  - [:computer: Dependencies](#computer-dependencies)
  - [Requirements](#requirements)
  - [:file_folder: How to install](#file_folder-how-to-install-and-use)

---

## :clipboard: About
This application is in development. The website has one goal - allow web schools
to manage their users and teachers, and have a better overview of all registered users.

Users can edit their own information. It's based on the project Gym manager developed during the classes from Rocketseat.
This project and readme.md, will be updated according to the project evolution.

---

### :white_check_mark: Features
* Teachers

- [x] Create instructors
- [ ] Edit instructors
- [x] Show instructors
- [ ] Delete instructors

* Students

- [ ] Create members
- [ ] Edit members
- [ ] Show members
- [ ] Delete members

---
## :computer: Technologies
* [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JavaScript](https://www.javascript.com/)
* [NodeJs](https://www.nodejs.org/)

---
## :computer: Dependencies
* [Express](https://expressjs.com/pt-br/)
* [Nunjucks](https://mozilla.github.io/nunjucks/)
* [Nodemon](https://nodemon.io/)
* [Browser Sync](https://browsersync.io/)

---

## Requirements
To execute this project, you need [Git](https://git-scm.com/) and [NodeJs](https://nodejs.org/en/) installed in your device.
It's recommended to use a code editor like [VsCode](https://code.visualstudio.com/).

---

## :file_folder: How to install and use
* First clone the repository with the command below.
```bash
    # Using Git bash, clone the repository
    $ git clone https://github.com/Guilherme-A-Santos/my-class.git
```

* After this, enter in the project main folder.

```bash
    # Changing directory in the terminal/CMD
    $ cd my-class
```
* Then install all dependencies using the command `npm install`.

```bash
    # Installing all dependencies
    $ npm install
```

* In a terminal, use the command `npm start` to allow the project to run.

```bash
    # Starting the project
    $ npm start
```

* Then open your browser (Google Chrome is the most recommended) and type in url *localhost:5000*

```bash
    # The project will run in the port:3000 if you're using browser-sync

    # You can acess too using the port:5000
```


You can use the routes in url.
Examples: http://localhost:5000/teachers/create and
http://localhost:5000/teachers/AN_USER_ID/
