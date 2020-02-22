# MLHacks (Azure QnA bot + NodeJS)
# Custom tailored.
This app demonstrates setting up a simple NodeJS app that connects to the QnA bot service on Azure. It makes the request by using a jQuery wrapper to an internal NodeJS endpoint that wraps the call to Azure. 


| Name  | Description  | Default  |
|---|---|---|
|  PORT | The port to run the webserver on | 3000  |
|  ENDPOINT |  The QnA bot endpoint URI |  undefined |
|  ENDPOINT_KEY | The EndpointKey to use with the specified ENDPOINT | undefined |


## Running locally
To run the app locally, simply run:
`yarn` to install the dependencies of the app and then `npm start` or `yarn start`
