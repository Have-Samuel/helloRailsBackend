![](https://img.shields.io/badge/Microverse-blueviolet)
# Hello React Rails Backend

An application that generates random greetings split into two repositories. One for the backend which is in Ruby on Rails, the other which is in React.

# Pull Request Link to Hello React Rails Frontend

## Built With

- Ruby on Rails
- React
## Additional Tools

- rubocop
- stylelint
- Ruby Gems
- npm

## Versions
- Ruby  ~3.1.2
- PostgreSQL  ~12.9
- Node.js  ~14.17.6
- Yarn  ~1.22.17

## `Getting Started`

To get a local copy of this project:

Clone this repository or download the Zip folder:
```
$ git@github.com:Have-Samuel/helloRailsBackend.git
```
Then:
```
$ cd helloRailsBackend

$ gem install bundler

$ bundle install
```

To start App:
```
$ rails server
```

To view on browser:
```
http://localhost:3000
```

## `Database creation`

Create a Postgres user:
```
$ su - postgres
```

After that access Postgres:
```
psql
```
```

Initialize the database:
```
$ bin/rails db:setup
```

Migrate the database:
```
$ bin/rails db:create
```
```

## front-end instructions
To get a local copy of this project:

Clone this repository or download the Zip folder:
```
$ git@github.com:Have-Samuel/helloFrontEnd.git
```
Then:
```
$ cd helloFrontend

$ gem install bundler

$ bundle install
```

To start App:
```
$ npm start
```

To view on browser:
```
http://localhost:3001
```

### To track linter errors locally follow these steps:

Track Ruby linter errors run:
```
$ rubocop
```
To auto-correct correctable Rubocop offenses run:
```
$ rubocop --auto-correct-all | rubocop -A
```

Track ESlint linter errors run:
```
$ npx eslint .
```
To auto-correct correctable Eslint errors run:
```
$ npx eslint . --fix
```

Track Stylelint linter errors run:
```
$  npx stylelint "**/*.{css,scss}"
```
To auto-correct correctable Eslint errors run:
```
$ npx stylelint "**/*.{css,scss}" --fix
```

## `Authors`

👤 **Have Samuel**

- GitHub: [Have-Samuel](https://github.com/Have-Samuel)
- Twitter: [@samhave1](https://twitter.com/@samhave1)
- LinkedIn: [Have Samuel Kabreebe](https://linkedin.com/in/Have-Samuel-Kabreebe)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Thanks Microverse for the guidlines.

## 📝 License

This project is [MIT](./MIT.md) licensed.