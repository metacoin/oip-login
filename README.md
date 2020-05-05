# oip-login

Log in to a service with a mnemonic and post OIP records 

## Install

```
npm install
```

## Setup

Configure your `.env` file using the example `.env_example` provided in the root directory.

## Run

```
npm start
```

Currently the program generates a new mnemonic and sends an OIP record to the chain using the RPC credentials and FLO address provided in the `.env` file. In the future we can use this high-level process to create modules for user login and sending OIP records as well as FLO payments.

### Notes

Currently including `"@babel/runtime": "7.0.0-beta.55"` because of an update to `babel` which is a dependency from `oip-protobufjs`. More info: https://github.com/meteor/meteor/issues/10128#issuecomment-410523377
