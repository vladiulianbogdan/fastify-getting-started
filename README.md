# Genezio Fastify Getting Started

In the index.mjs file, you will see a very basic Fastify.js application that is set up to be deployed as a Genezio function. It handles a couple of requests (/ and /users).

You can update the Fastify application and then add a front-end to your application:

1. Create a client/index.html file.
2. Update the genezio.yaml file and add a frontend section:

```
frontend:
  path: client
  publish: .
```

Then, in the client/index.html file, you can simply fetch data from the Fastify web app. You can see the Fastify app's URLs by clicking the "View your URLs" button in the editor.

[![Deploy to Genezio](https://raw.githubusercontent.com/Genez-io/graphics/main/svg/deploy-button.svg)](https://app.genez.io/start/deploy?repository=https://github.com/Genez-io/fastify-getting-started)
