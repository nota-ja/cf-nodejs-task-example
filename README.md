# cf-nodejs-task-example

## Quick Try

```
cf push
```

In another terminal:
```
cf logs nodetask
```

In original terminal:
```
cf run-task nodetask "env"                   # shell command example
cf run-task nodetask "node -v"               # node command example
cf run-task nodetask "coffee -h"             # example for command under node_modules/.bin/
cf run-task nodetask "npm run coffee-help"   # example for script registered in package.json
```
