<p align="center">
  <a href="" rel="noopener">
  <img src="./diagram.png" alt="Database schema"></a>
</p>
<h3 align="center">Voting system</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/tomitheninja/elections.svg)](https://github.com/tomitheninja/elections/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/tomitheninja/elections.svg)](https://github.com/tomitheninja/elections/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)

</div>

---

<p align="center">An implementation for an election system I implemeneted for the databases and the cross-platform mobile development courses at the University of Szeged.
    <br>
</p>

## 📝 Table of Contents

- [Problem Statement](#problem_statement)
- [Dependencies / Limitations](#limitations)
- [Setting up a local environment](#getting_started)
- [Data schema](#data_schema)
- [Technology Stack](#tech_stack)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## 🧐 Problem Statement <a name = "problem_statement"></a>

In today's world, it is important to express our opinion on a subject.

Thanks to elections, the most important positions and roles in society are given to the best avaiable candidates.

Nowadays, almost everyone has access to the internet.
For this reason, it is logical to handle voting by computer systems.

This project makes it possible to organize small and medium-sized elections.

## 💾 Database schema <a name = "data_schema"></a>

## ⛓️ Dependencies / Limitations <a name = "limitations"></a>

- MySQL database, version 8
- NodeJS runtime, version 16
- Flutter
- (optional) docker, docker-compose

## 🏁 Getting Started <a name = "getting_started"></a>

The server can be deployed on either your host machine or in a docker container.

Only the native method will be described here.

### Prerequisites

You should have the nodejs runtime and mysql >= 8 installed on your local machine.

### Installing

Configure the server through environment variables

See [the example](./server/.env.example)

Install nodejs dependencies

```sh
$ npm install
```

Generate the ORM library from the schema

```sh
$ npx prisma generate
```

Build the server

```sh
$ npm run-script build
```

## 💾 Data schema <a name="data_schema"></a>

TODO: Add notes about how to use the system.

## ⛏️ Built With <a name = "tech_stack"></a>

- [MySQL](https://www.mysql.com/) - Database
- [NodeJs](https://nodejs.org/en/) - Server Environment
- [Flutter](https://flutter.dev/) - Cross platform UI development kit

## ✍️ Authors <a name = "authors"></a>

- [Tamás Südi](https://github.com/tomitheninja) - Author
