# OpenLayers + esbuild

This example demonstrates how the `ol` package can be used with [esbuild](https://esbuild.github.io/).

To get started, run the following (requires Node 12+):

    npx create-ol-app my-app --template esbuild

Then change into your new `my-app` directory and start a development server (available at http://127.0.0.1:8000/):

    cd my-app
    npm start

To generate a build ready for production:

    npm run build

Then deploy the contents of the `dist` directory to your server.
