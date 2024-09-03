# MyApi (v1)
A REST API to obtaininteract with information regarding persons, drivers and their cars.

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

#### Persons routes:
| Type     | Route        | Description         |
| ----     | -----        | -----------         |
| `POST`   | /api/persons | Create a new person |
| `GET`    | /api/persons | Show all persons    |
| `GET`    | /api/persons/id/:id | Get a person by ID |
| `GET`    | /api/persons/name/:name | Get a person by name |
| `GET`    | /api/persons/idcard/:idcard | Get a person by ID card |
| `PUT`    | /api/persons/:id | Edit a person |
| `DELETE` | /api/persons/:id | Delete a person |


## Prerequisites
Having NodeJS installed (https://nodejs.org/en/download/prebuilt-installer/current)

## Installation
Use the command line inside the project's folder:

```bash
npm install
```

## Run
Run the project in VSCode, with or without debugging, or run in the command line inside the project's folder:

```bash
node app.js
```
