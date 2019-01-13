# Basic HelloWorld React Rails

Web application that uses rails + react + redux store + webpack. It's a default react with rails hello world example that I am building. I will add any new additions as need be. I only built this so that I could reference it later on. When building another web application.

## Installation/Usage
Be sure to have yarn and nodejs installed before usage

```bash
cd basic-react-rails
bundle && yarn
foreman start -f Profile.hot
```

## Setup on your own
**Basic Bash Commands For Installation**

Commands came form [react_on_rails gitbook](https://shakacode.gitbooks.io/react-on-rails/content/docs/tutorial.html)

```bash
rails new my_app --webpack=react
# be sure to git commit changes
rails generate react_on_rails:install
bundle && yarn
```

or

```bash
bundle exec rails webpacker:install
yarn add "rails/webpacker" # because the installer has a bug that puts in an invalid version in your package.json.
bundle exec rails webpacker:install:react
yarn add --dev webpack-dev-server
run rails generate react_on_rails:install && bundle && yarn
```

**Important npm packages can be found in client/package.json**

## How Redux Works

![Redux IMG](https://1npo9l3lml0zvr6w62acc3t1-wpengine.netdna-ssl.com/wp-content/uploads/2017/05/redux-cycle.jpg)
