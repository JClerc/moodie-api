<h1 align="center">
  <img alt="moodie-server" width="652" src="https://jclerc.github.io/assets/repos/banner/moodie-server.jpg">
  <br>
</h1>

<p align="center">
  <img alt="made for: school" src="https://jclerc.github.io/assets/static/badges/made-for/school.svg">
  <img alt="language: javascript" src="https://jclerc.github.io/assets/static/badges/language/javascript.svg">
  <img alt="made in: 2016" src="https://jclerc.github.io/assets/static/badges/made-in/2016.svg">
  <br>
  <sub>Moodie server, to manage connected lights and background services.</sub>
</p>
<br>

## Features

- [x] Detect and update light's color depending on mood
- [x] Hook into services (music, weather, ...)
- [x] CLI and web interface
- [x] Interact with Moodie app

## Stack used

- Koa `1.2.4`
- Socket.io `6.0.0`
- Nodemon `1.11.0`

## Getting started

#### Requirements

- `yarn` (or `npm`)

#### Installation

```sh
git clone https://github.com/jclerc/moodie-server.git
cd moodie-server
yarn # or `npm i`
yarn start # or `npm start`
```
