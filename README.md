# **Aruppi API** (v4.0.0)

> This API has everything about Japan, from anime, music, radio, images, videos ... to japanese culture
>
> These are the services used for the Aruppi App (only available in Spanish language)

![node version](https://img.shields.io/badge/node->=12.17.x-brightgreen.svg)
![npm version](https://img.shields.io/badge/npm->=6.14.x-brightgreen.svg)
![yarn version](https://img.shields.io/badge/yarn->=1.22.x-brightgreen.svg)
![type code](https://img.shields.io/badge/aruppi-API-brightgreen.svg)
![maintenance](https://img.shields.io/badge/maintained-Yes-brightgreen.svg)
![now](https://badgen.net/badge/icon/now?icon=now&label)
![gitrepo](https://img.shields.io/github/stars/aruppi/aruppi-api?style=social)

---

<img src="./assets/img/logo.png" width="100%" alt="">

## 📖 API Documentation

Soon we will add the documentation information in a link

## :rocket: Custom Aruppi API Link

Link to access the [Aruppi API](https://aruppi-api.jeluchu.now.sh/api/v2)

## 📚 **Development Diary**

Describe the purpose of the project and give clues about what the code does.
For more information go to the following link [Diary Reference](./development_diary/README.md).

## **:wrench: Developer usage**

### **Set up project**

Before cloning the repo **be sure** you have installed:

- [**NODE**](https://www.google.com/search?q=how+to+install+node) (version >= 12.17.x)

In your package manager you can use either **yarn** or **npm**,
you need to have installed these versions:

- [**NPM**](https://www.google.com/search?q=how+to+install+npm) (version >= 6.14.x)
- [**YARN**](https://www.google.com/search?q=how+to+install+yarn) (version >= 1.22.x)

Then:

- Choose a folder project in your system and switch in `cd [folder path]`
- Clone the repo in your folder path `git clone https://github.com/aruppi/aruppi-api`

---

### **Installation**

In order to install the project and all dependencies, enter in the project folder and run `npm install`
or you can do the same with yarn with `yarn` in the project

---

### Start the project

```bash
npm start
```

or

```bash
yarn start
```

### Build the Project

```bash
npm build
```

or

```bash
yarn build
```

### Test the project

```bash
npm test
```

```bash
yarn test
```

---

## Documentation for the V4 of the API

First of all you need to have installed **yarn** or **npm**, the required versions that
we mentioned above in this README, we need to have installed too **MongoDB** (you can configure
the port for the database in the .env file).

In order to install and migrate the data to the database, we need to have some scripts first for each collections that you want to have in the database.

Installing **mongodb** in **Linux**:

- First we need to install **MongoDB Community**, in this link you have a more specific installation method - [MongoDB Community Version 4.4 for Ubuntu 20.04 (Focal)](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/)
- After these you only need a **sudo systemctl status mongod** to check if the service of mongo is already running, if all is good you can continue with the docs
- Next step is migrating the data from the JSON's to the database, in this case we are having a separate folder for these scripts

Running the scripts for the poblation of the database of **mongodb**:

- We need to download the **mongoScripts** folder, in order to run all of these scripts, we need to run first (if you have npm, it would be **npm install** to install all the dependencies of this folder) **yarn** to install the dependencies
- After installing the dependencies of this folder, next we are building the project what is in TypeScript and we need to build to JavaScript, we do a **yarn build** (in npm would be **npm build**)
- Next in order to migrate all the information from the JSON files, we are going to execute the following commands (if you have npm, the only difference is change the word of **yarn** to **npm**): **yarn radio**; **yarn genre**; **yarn theme**; **yarn directory**; **yarn waifu**;
 


## Deprecated v1 for API

Aruppi has grown since it was launched and we need to continue improving the application along with the services to be able to give new features.

But if you need to see the code or the operation of the old version you can do it

- [Aruppi API GitHub (v1) [Deprecated]](https://github.com/aruppi/aruppi-api-v1)
- [Aruppi API Custom Link(v1) [Deprecated]](https://aruppi.herokuapp.com/api/Aruppi/)

## Countdown to deprecation of v2 API

Aruppi has grown since it was launched and we need to continue improving the application along with the services to be able to give new features.

At this time version 2.6.9 will remain functional until Aruppi App users fully migrate to version 1.5.0 of the app

## **:handshake: Contributing**

- Fork it!
- Create your feature branch: `git checkout -b my-new-feature`
- Commit your changes: `git commit -am 'Add some feature'`
- Push to the branch: `git push origin my-new-feature`
- Submit a pull request

---

### **:busts_in_silhouette: Credits**

- [Darkangeel](https://github.com/Darkangeel-hd) (System administration authority (SYSADM))
- [Jéluchu](https://github.com/Jeluchu) (Android Developer, designer, and others)
- [Capitanwesler](https://github.com/capitanwesler) (Backend developer, web developer and others)

---

### **:heart: Show your support**

Please :star: this repository if you like it or this project helped you!\
Feel free to open issues or submit pull-requests to help me improving my work.

---

### **📚 Projects that use the API**

<table>
  <tr>
    <td align="center">
      <a href="https://aruppi.jeluchu.com/">
        <img src="https://avatars2.githubusercontent.com/u/38753425?s=200&v=4" width="75px;" alt="Jeluchu"/><br />
          <sub>
            <b>Aruppi</b>
          </sub>
      </a><br/>
        <sub>Anime y Manga</sub>
      </a>
    </td>
        <td align="center">
      <a href="https://fmaldonado6.github.io/Akiyama/">
        <img src="https://raw.githubusercontent.com/Fmaldonado6/Akiyama/master/images/logo/web-logo.png" width="75px;" alt="Jeluchu"/><br />
          <sub>
            <b>Akiyama</b>
          </sub>
      </a><br/>
        <sub>Web and App</sub>
      </a>
    </td>
  </tr>
</table>

### **:robot: Author**

_*Jéluchu*_

> You can follow me on
> [github](https://github.com/Jeluchu)&nbsp;&middot;&nbsp;[twitter](https://twitter.com/Jeluchu)

---

Copyright © 2020 [Jéluchu](https://about.jeluchu.com/).
