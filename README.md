# Boilerplate theme [![](https://badge.fury.io/js/jsonresume-theme-boilerplate.svg)](https://www.npmjs.org/package/jsonresume-theme-boilerplate)

This is the boilerplate theme for [JSON Resume](http://jsonresume.org/).

## Getting started

To get started with theme development, this is what you'll need:

- [node.js](http://howtonode.org/how-to-install-nodejs)
- [npm](http://howtonode.org/introduction-to-npm)

If you're on Linux, you can simply run:

```
sudo apt-get install nodejs-legacy npm
```

Or if you're on OSX and got [Homebrew](http://brew.sh/) installed:
```
brew install node
```

### Install the command line

We're going to use the official [resume-cli](https://github.com/jsonresume/resume-cli) to run our development server.

Go ahead and install it:

```
sudo npm install -g resume-cli
```

### Download theme

Clone the repository
```bash
git clone https://github.com/konalexiou/jsonresume-theme-papirus
```

### Install npm packages

We need to install the dependencies. `cd` into the theme folder we just downloaded and run:

```bash
sudo npm install
```

This will read the local `package.json` and install the packages listed under `dependencies`.

### Serve theme

While inside the theme folder, simply run:

```
resume serve
```

You should now see this message:

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

Congratulations, you've made it!

## Deployment

If you are familar with NPM, you should be done with this in no time.

If you already have an NPM account, you can run `npm login` and enter your username and password. If not, you can run `npm adduser` and fill in the proper fields.

If you changed the dependencies or added new ones, you'll want to run `npm install` again, and just to make sure, run `npm update` to get the latest version of each dependency.

When you are done with that, you may go into your package.json, and edit the version number. When all of the above is finished, you may run `npm publish` to release your theme to the public. Now everyone can use your theme with their resume.

When updating your theme, you'll need to change the version number and run `npm publish` again.

## License

Available under [the MIT license](http://mths.be/mit).
