### Cognito infrastructure for react-cognito frontend

Backend for [react-cognito](https://github.com/s4nt14go/react-cognito) frontend.
   
#### Deployment instructions

1. Use Node 14 version, using [nvm](https://github.com/nvm-sh/nvm) you can:

    ```
    # set Node 14 in current terminal
    nvm use 14
    # set Node 14 as default (new terminals will use 14)
    nvm alias default 14
    ```
   
1. Install dependencies and deploy on your stage (provided you configured your AWS credentials)

    ```shell script
    npm ci
    # deploy on dev stage
    npm run deploy
    ```