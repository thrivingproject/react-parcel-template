# Light React App

Requires [Node.js](https://nodejs.org/en).

## Installation and Usage

After creating a repository from this template, clone it and run:

```bash
npm i
# Start development server
npm start
```

## Structure

```bash
# The app is designed to be developed with the following structure:
.
├── src
│   ├── components
│   ├── pages
│   │   └── Home.jsx
│   ├── App.jsx
│   ├── index.html
│   └── index.js
├── README.md
├── package-lock.json
└── package.json
```

## How This Template Was Created

```bash
npm init -y
npm i --save-dev parcel
npm i react react-dom react-router-dom
```

Add the script `"start": "parcel public/index.html"` in `package.json`
