# Steps To Reproduce

```bash
npm init -y
npm i --save-dev parcel && npm i react react-dom react-router-dom
mkdir src public
touch public/index.html src/index.js src/App.jsx
```

Create the script `"start": "parcel public/index.html"` in `package.json`

Run `npm start`
