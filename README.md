# JS Personal API

[![codecov](https://codecov.io/gh/chrisvogt/js-personal-api/branch/master/graph/badge.svg)](https://codecov.io/gh/chrisvogt/js-personal-api) [![Build Status](https://travis-ci.org/chrisvogt/js-personal-api.svg?branch=master)](https://travis-ci.org/chrisvogt/js-personal-api)

This repository contains a personal API used to aggregate data from various online providers. The goal of creating this project is to dogfood this instead of the [static data I'm currently using](https://chrisvogt.firebaseio.com/v1.json) to power my website. This project is new and is not stable. Use at your discretion.

##### Supported Providers

Following are the providers I intend to integrate with.

- [x] GitHub
- [ ] Twitter
- [ ] Flikr

### » Install

Use npm to install dependencies.

```
npm install
```

Create a new file at `.env` containing your database credentials.

```
FIREBASE_API_KEY=YOUR_API_KEY
FIREBASE_DATABASE_URL=https://YOUR_DATABASE_URL.firebaseio.com
FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
```

### » Commands

The following npm commands are available.

* `build` — runs all tasks necessary to start
* `start` — starts the local web server
* `sync:repositories` — get or sync repositories for all projects
* `report-coverage` — report to Codecov
* `test` — runs the unit tests
