# Getting started with a simple flow function

This flow function exposes a HTTP endpoint. You can submit any data to the endpoint via HTTP POST and the flow function will echo it back to you in the HTTP response.

1. Fork this repo into your own GitHub account.
2. Go to [Flows.network](https://flows.network/flow/new) to create a new flow.
3. Import the forked repo from your account into flows.network.
4. Build and deploy.
5. You will now get a URL endpoint from the flow function. You can test it as follows.

The example below shows how to query a flow function we have already deployed.

```
curl -X POST http://www -d "I am a Rustacean"
```
