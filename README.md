# Usage

## Development setup

### Pre-setup

1. make sure you have `Node.js` version **12** or `nvm`
2. make sure you install `Docker Desktop`
3. commands in `steps` are for bash, fish shell will replace `&&` with `&`

### Steps

1. clone project
2. `cd` into project
3. run `npm install && cd backend && npm install && cd ../frontend && npm install && cd ..`
4. run `docker-componse build && docker-compose up -d`

_I previously had docker run `npm install` as well, the downside is `node modules` are require in local in order for development. Therefore, I removed those functionalities and require user to build on local then run in container._

## Service URL

Frontend: `http://localhost:3000`
<br/>
Backend: `http://localhost:8080`

## Test

### Backend

1. open terminal
2. go to `<project directory>/backend`
3. run `npm run test`

### Frontend

I currently do not know how to build unit test and UI test, will continue add into this project in future.
