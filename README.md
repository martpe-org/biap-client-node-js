# Introduction

A node js rest api server which sits between ONDC protocol layer and react app in browser

# For whom

anyone who want to refer for building a UI friendly API on protocol layer

# Server side Events(SSE)

- Since each request response is async in ONDC, when we receive data from protocol layer we communicate it to browser as soon as possible with SSE
- Opens the connection at the time of first response from protocol layer that needs to be communicated to browser

# Build with nodejs

- using express js
- Implements referral implementation of payment integration with Juspay

# To run locally

```bash
yarn add or npm install
yarn debug or npm debug
```

# To build

```bash
yarn add or npm install
yarn start or npm start
```

---

# For MartPe

## Initial Steps for local setup

1. clone this repo locally.

2. Follow the [video](https://www.youtube.com/watch?v=deEYHVpE1c8&ab_channel=FaradayAcademy) for the local git configurations setip as this is a forked repo.

3. MartPe uses <a href="https://github.com/martpe-org/biap-client-node-js/tree/martpe-dev">martpe-dev</a> as the base branch, which is a branch cut from v1.2.0 branch of upstream. Any new upstream features can be fetched from the below command.

```bash
git pull upstream
```
