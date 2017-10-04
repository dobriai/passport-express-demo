## Intro

This example is based on Jared Hanson's original example https://github.com/passport/express-4.x-facebook-example, for which I am immensely grateful!

This example demonstrates how to use [Express](http://expressjs.com/) 4.x and
[Passport](http://passportjs.org/) to authenticate users using any number of provders.

It is mostly intended for my own education and testing of... well, various things.

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:dobriai/passport-express-demo.git
$ cd passport-express-demo
$ yarn # OR: npm install
```

The example uses environment variables to configure the consumer key and
consumer secret needed to access Google's API.  Start the server with those
variables set to the appropriate credentials.

```bash
$ GOOGLE_CLIENT_ID=<your_app_id> GOOGLE_CLIENT_SECRET=<your_app_secret> node server.js
```

Open a web browser and navigate to [http://localhost:3000/](http://localhost:3000/)
to see the example in action.
