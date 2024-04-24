# freeCodeCamp - Request Header Parser Microservice Project

## Summary

This is one of the projects that requires implementation as part of [freeCodeCamp's Back End Development and APIs Certification](https://www.freecodecamp.org/learn/back-end-development-and-apis/).

As part of the [requirements](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/request-header-parser-microservice) (including utilising the [boilerplate code provided by freeCodeCamp](https://github.com/freeCodeCamp/boilerplate-project-headerparser/)), this project involves implementing an application that returns a JSON object via API containing `ipaddress`, `language` and `software` values from your browser.

## Setup

This project uses Node.js and Express in order to run this application. As such, make sure that Node.js and npm are installed and then run the following commands in your terminal, within the project's directory:

```
npm install
npm start
```

## Usage

#### Example

```
<YOUR_PROJECT_URL>/api/whoami
```

#### Output

```json
{
  "ipaddress": "159.20.14.100",
  "language": "en-US,en;q=0.5",
  "software": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"
}
```

