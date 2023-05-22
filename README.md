# stracciatella

Boilerplate for a simple vanilla JS front-end app with components and state management

https://javascript.plainenglish.io/building-a-modern-web-app-without-frameworks-classes-components-inheritance-1bfd314fc582

# npm audit report

minimatch  <3.0.5
Severity: high
minimatch ReDoS vulnerability - https://github.com/advisories/GHSA-f8q6-p94x-37v3
fix available via `npm audit fix --force`
Will install serve@14.2.0, which is a breaking change
node_modules/serve-handler/node_modules/minimatch
  serve-handler  1.1.0 - 6.1.3
  Depends on vulnerable versions of minimatch
  node_modules/serve-handler
    serve  7.0.0 - 14.0.1
    Depends on vulnerable versions of serve-handler
    node_modules/serve

3 high severity vulnerabilities


## Requirements

node version `15.14.0`

## Install

npm i

## Commands

weback in watch mode - `npm start`

production - `npm run build`

testing - `npm run test`

prod hosting - `npm run host`
