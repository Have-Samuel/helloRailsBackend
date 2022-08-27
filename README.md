# Hello-rails-back-end
This litte API provides different greetings

## Getting Started
 Link for the front end [repo](https://github.com/Have-Samuel/hello-frontend/pull/1)
  * Clone the repo and run the following commands on the terminal
```
 git clone https://github.com/Have-Samuel/helloRailsBackend.git

 cd helloRailsBackend

bundle install

```

* Go to config/database.yml
* After default put
```
username: your_postgres_database_username
password: your_postgres_database_password
```

Finally run

```
rails db:create db:migrate db:seed

rails s

```
