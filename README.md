# create-react-app-add-redux
This package adds a basic Redux cycle to the React boilerplate generated by `create-react-app`.

## Installation
Run the following commands to install `create-react-app` and `create-react-app-add-redux`:

```
npm i -g create-react-app
npm i -g create-react-app-add-redux
```

## Usage
First create a new app using `create-react-app`

```
create-react-app my-app
cd my-app
add-redux
```

Now the dependencies have been ejected
and Redux has been installed and scaffolded.

Alternatively, if you want an alias for those three commands, you can paste this into your aliases file:

```
  add-react-redux-app() {
    create-react-app "$1";
    cd "$1";
    add-redux;
  }
```

This will let you run `add-react-redux-app my-app` to automatically create both the React boilerplate and Redux cycle inside of my-app.
