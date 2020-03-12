# todo-list

> docker intro sample front end app

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9090
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

### App Config

The application has the following env variables for configuration

API_PORT_8000_TCP_ADDR : Backend API host address 

API_PORT_8000_TCP_PORT : Backend API port where the api is running

API_URL: Will replace API_PORT_8000_TCP_ADDR API_PORT_8000_TCP_PORT as the full API URL

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

### Pending Taks

- [x] Create TODO list app
- [x] Update to use API instead of just state
- [ ] Unit Testing
- [ ] Handle Environemts via ENV variables
- [ ] Create Docker File