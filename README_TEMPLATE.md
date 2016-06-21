[![Build Status](https://travis-ci.org/chkakaja/sentimize.svg?branch=master)](https://travis-ci.org/chkakaja/sentimize)

[![Stories in Ready](https://badge.waffle.io/chkakaja/sentimize.png?label=ready&title=Ready)](https://waffle.io/chkakaja/sentimize)

# Microservice Name
Application description

## Table of Contents
1. [Getting started](#getting-started)
2. [Tech](#tech)
3. [Database Schema](#database-schema)
4. [Team](#team)
5. [Contributing](#contributing)

## Getting started

Clone and install dependencies:
```sh
$ git clone ____
$ cd ____
$ npm install
```
Create `env/development.env` and set environment variables. Follow `env/example.env`.

add any additional needed commands and instructions here

```sh
$ npm run bundle
$ npm start
```

#### Testing

Configure the environment variable `NODE_ENV` prior to running tests.

 ```sh
$ export NODE_ENV=development
$ npm test
```

## Tech
> List any libraries, APIs, and tech stack here

## Database Schema
> Add schema for application db here

## Directory Layout
> Use the diagram below as an example and starting point
```
├── /env/                       # Environment variables
├── /node_modules/              # 3rd-party libraries and utilities
├── /client/                    # Client source code
│   ├── /build/                 # Build file produced with Browserify
│   ├── /components/            # React components
│     ├── /home-view/           # Home view components
│     ├── /main-layout/         # Main Layout components
│     ├── /record-view/         # Record view components
│     ├── /report-view/         # Reporting view components
│     ├── /App.jsx/             # Main React App
│   ├── /lib/                   # Lib files, e.g. from FACE API
│   ├── /style/                 # CSS Style files
│   ├── /index.jsx              # Index file to attach React to DOM
├── /server/                    # Server source code
│   ├── /config/                # Initial server config files
│   ├── /controllers/           # Controllers for database interaction
│   ├── /lib/                   # Lib for util functions
│   ├── /models/                # Data models
│   ├── /routes/                # Routes for incoming GET and POST requests
│   ├── /views/                 # Jade templating views
│   └── /server.js              # Server-side startup script
├── /test/                      # Server and client side tests
│   ├── /client/                # Client side tests
│   ├── /server/                # Server side tests
|   ├── /data/                  # Holds seed & dummy data
└── package.json                # List of 3rd party libraries and utilities to be installed
└── .babelrc                    # Babel presets
└── .eslintrc                   # ESLint settings
```

## Team
  - Product Owner:            [Leo Adelstein](https://github.com/leoadelstein)
  - Scrum Master:             [Jack Zhang](https://github.com/jackrzhang)
  - Development Team Members: [Leo Adelstein](https://github.com/leoadelstein), [Jinsoo Cha](https://github.com/jinsoocha), [Will Tang](https://github.com/willwtang/shortly-deploy), [Jack Zhang](https://github.com/jackrzhang)

## Contributing
See [STYLE-GUIDE.md](https://github.com/gobble43/docs/blob/master/STYLE-GUIDE.md) and [CONTRIBUTING.md](https://github.com/gobble43/docs/blob/master/CONTRIBUTING.md) for contribution guidelines.
