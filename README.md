# Blanja Web <img src="https://img.shields.io/badge/Build%20with-ReactJs-61dbfb?style=popout&logo=react">

<div align="center">
    <img width="250" src="./src/assets/img/img/logo.png">
</div>

## Contents

- [Description](#description)
- [Features](#features)
- [Requirements](#requirements-for-development)
- [Installation](#installation-for-development)
- [Screenshoots](#screenshoots)
- [Demo Blanja Web](#demo-blanja-web)
- [Related Project](#related-project)

## Description

**Blanja Web** sebuah e-commerce dimana customer bisa membeli suatu produk yang diinginkan hanya dengan sekali klik. Sebagai seller bisa berjualan tanpa harus memikirkan tempat. Web ini dibangun menggunakan ReactJS,ExpressJS dan NodeJS.

## Features

- Order product
- History transaction
- Add product (sellers only)
- Edit profile
- Reset Password
- etc

## Requirements for Development

- [`Node Js`](https://nodejs.org/en/)
- [`npm`](https://www.npmjs.com/get-npm) or
- [`yarn`](https://classic.yarnpkg.com/en/docs/install/#debian-stable)
- [`ReactJs`](https://reactjs.org/)
- [`Blanja Backend`](https://github.com/Shhb0420/Blanja-API.git)

## Installation for Development

1. Buka terminal / command prompt
2. `git clone https://github.com/Shhb0420/BlanjaApps-using-react`
3. Buat folder di direktori dan ketik `npm install` untuk menginstall dependencies
4. Buat file **_.env_** di direktori dengan konten berikut :

```bash
REACT_APP_URL = "http://host_backend:port_backend"
```

Contoh :

- http://host_backend:port_backend is http://localhost:2005

kamu bisa menulis didalam .env seperti ini :

```bash
REACT_APP_API_URL = "http://localhost:2005"
```

5. Sebelum menjalankannya, anda harus mengintall backend terlebih dahulu.
6. `npm start` didalam terminal untuk memulai project.

## Screenshoots

<div align="center">
    <img width="100%" src="./src/assets/img/screenshoot-1.png">
    <img width="100%" src="./src/assets/img/screenshoot-2.png">
    <img width="100%" src="./src/assets/img/screenshoot-3.png">
</div>

## Demo Blanja Web

Blanja web versi build, silahkan klik link dibawah ini.

<a href="http://54.204.68.100:3000/">
  <img src="https://img.shields.io/badge/Blanja%20Web-Link%20Demo-blue.svg?style=popout&logo=firefox"/>
</a>

## Related Project

RESTful API untuk web aplikasi ini, Clone repository untuk menjalankannya.

<a href="https://github.com/Shhb0420/Blanja-API">
<img src="https://img.shields.io/badge/Blanja%20Backend-Repository-blue.svg?style=popout&logo=github"/>
</a>
