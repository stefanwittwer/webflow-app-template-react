# example-webflow-app-react

This is an example Webflow Designer extension written in TypeScript to get you started. Check out Webflow's [documentation](https://docs.developers.webflow.com/v2.0.0/docs/create-a-designer-extensions) for in-depth information about Designer Extension features and API.

## Developing

Run `$ yarn` to install dependencies in this project.

```
$ yarn dev
```

The above command does a few things:

- Watches for changes in the `src/` folder and bundles the React application in the `public/` folder, as required by the Webflow CLI for bundling.
- Spins up a process that serves your extension files from under `public/`

The command outputs the URL under which your extension is being served. Use this as the “Development URL” for your app in the Webflow Designer’s Apps panel. You can then launch the extension from the same place.

## Deploying

```
$ yarn build
```

This will take the contents of the `./public` folder and prepare a `bundle.zip` file ready for you to upload as a Designer extension for your App.
