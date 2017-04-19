# VueJS Tutorials

VueJS Tutorials is an open source VueJS tutorial sharing platform. The focus of the project is to provide a one stop shop for everything someone may be interested in learning about VueJS. It uses VueJS 2 as the front end framework and Firebase as the backend.

The foundation of the project is based upon chinchang's excellent [vuejsfire-hackathon-starter](https://github.com/chinchang/vuejsfire-hackathon-starter).
---
[Detailed Wiki](https://github.com/chinchang/vuejsfire-hackathon-starter/wiki/)
---

### Features

- Built over Vuejs' [webpack-simple template](https://github.com/vuejs-templates/webpack-simple)
- ES6 ready
- Single file components
- In-built User Module
- Twitter/Facebook Authentication
- In-built notification system
- Beautiful design and experience
- Responsive UI

### Ingredients

- [Vue.js webpack-simple template](https://github.com/vuejs-templates/webpack-simple)
- [Firebase](https://firebase.google.com)
- [Material Design Icons](https://materialdesignicons.com/)
- Page loader by [Tobias Ahlin](http://tobiasahlin.com/spinkit/)
- [Roboto](https://fonts.google.com/specimen/Roboto) font from Google fonts

### Getting started with development

- Clone this repo.
- Create a project in [Firebase](https://console.firebase.google.com/). Note, the app would also run with the default Firebase config included in the project. But its advised to replace it with your own Firebase project.
- Turn on [Twitter](https://firebase.google.com/docs/auth/web/twitter-login) & [Facebook](https://firebase.google.com/docs/auth/web/facebook-login) in your Firebase project.
- Replace the Firebase credentials in `auth.js`.
- Run `npm install` to install all dependencies.
- Run `npm run dev` to spin the local server and access your cool app on `localhost:8080`.

### Deployment

- Run `npm run build` to build the project.
- If you are using Github pages for deployment, you can simply run `build-gh-pages.sh` instead.

[Read more about deployment](https://github.com/chinchang/vuejsfire-hackathon-starter/wiki#deployment).

### Contributing

- Fork the repo
- Make modifications
- Send a pull request

Simple!

### License

Open source under The MIT License
