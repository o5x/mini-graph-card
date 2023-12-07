# Build steps to generate mini-graph-card-bundle.js

```sh
sudo apt update
sudo apt install npm
npm install --save-dev rollup rollup-plugin-node-resolve @rollup/plugin-json rollup-plugin-serve @rollup/plugin-commonjs
npm install eslint --save-dev
npm run build
```

Source in `dist/mini-graph-card-bundle.js`
