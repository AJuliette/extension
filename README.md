## Configuration for an add-on

# How it works

1. Download the repo

2. Make the following commands:

```yarn add -D html-webpack-plugin```

```yarn add -D copy-webpack-plugin```

```yarn add -D css-loader```

```yarn add -D style-loader```

```yarn webpack```

It will create a `dist` folder.

3. On the add-on page of your browser, add this dist folder.

4. For a constant update of your app in development, use:

```yarn webpack --watch```