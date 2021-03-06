React Boilerplate
=====================

A minimal and light dev environment for ReactJS, courtesy of [nolotz](https://github.com/nolotz/react-simple-boilerplate)

### Usage

Install the dependencies and start the server.

```
npm install
npm start
open http://localhost:3001
```

### Static Files

You can store static files like images, fonts, etc in the `build` folder.

For example, if you copy a file called my_image.png into the build/images folder you can access it using `http://localhost:3000/build/images/my_image.png`.

### Linting

This boilerplate project includes React ESLint configuration.

```
npm run lint
```

### Dependencies

* React
* Webpack
* [babel-loader](https://github.com/babel/babel-loader)
* [webpack-dev-server](https://github.com/webpack/webpack-dev-server)
