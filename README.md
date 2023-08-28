# Getting started with a simple flow function

This flow function exposes a HTTP endpoint. You can submit any data to the endpoint via HTTP POST and the flow function will echo it back to you in the HTTP response.

1. Fork this repo into your own GitHub account.
2. Go to [Flows.network](https://flows.network/flow/new) to create a new flow.
3. Import the forked repo from your account into flows.network.
4. Build and deploy.
5. You will now get a URL endpoint to access the flow function. It is under the *Webhook Endpoint* section on the flows.network web site. You can test it as follows.

The example below shows how to query a flow function we have already deployed.
You can type the following URL into any browser's address bar:

```
https://code.flows.network/webhook/5VtSyNi1Vcsd4wQDgmcH?msg=I+am+a+Rustacean
```

Or, you can use the `curl` command to access the flow function.

```
curl https://code.flows.network/webhook/5VtSyNi1Vcsd4wQDgmcH?msg=I+am+a+Rustacean
```
