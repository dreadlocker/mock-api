npm i -D cross-env@5.2.0 npm-run-all@4.1.5 json-server@0.15.0

in package.json:
  "scripts": {
    "prestart:api": "node tools/createMockDb.js",
    "start:api": "node tools/apiServer.js",
  },