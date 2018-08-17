# Meteor Boilerplate

A fast and highly customisable Meteor.js boiler plate app.
The UI is handled by Material Design and the performance is achieved 
by selective tree-shaking and judicious use of dynamic imports, to
keep the client bundle as small as reasonably possible.

* Front end: [React](https://reactjs.org/) ✌️
* UI: [MUI](https://material-ui.com/) (Material Design) 🎨
* Bundle size: [<250kB gZipped](https://www.ninjapixel.io/meteor-bundle-size.html) 🐭
* Styling: [JSS](http://cssinjs.org/) 💅
* Security: Users, roles and groups 🔐
* Email: Simply add the SMTP property to the settings file and you can send emails. The boilerplate comes with a password reset email out of the box 📧
* Themes: Set your own colour schemes and font 🖍️



For some background information on the performance enhancements in this app, check out [this blog post](https://www.ninjapixel.io/meteor-bundle-size.html).

## Start Guide



### Project setup

The root directory contains some general setup, such as linting, and leaves space for including other items such as end-to-end
tests and a react native app.

From the root directory, install packages by running:

```
npm i
```

The `meteor` app lives in the `/app` directory. To setup and
run the app itself, run the following in your terminal: 

```
cd app
meteor npm i
npm start
```