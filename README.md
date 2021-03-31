# Rails-Bootstrap-Devise Boilerplate

This is a startup rails 6 application/boilerplate where you can avoid adding bootstrap and devise gem from scratch. This bolierplate will encourage you to start directly with your main tasks. 

You will find following items in this startup rails application:

* Bootstrap 4.3, JQuery, Popper.js integrated using webpacker
* Font Awesome 5 integrated using webpacker
* Devise implemented with customised bootstrap forms for sessions, registrations and passwords
* Letter opener implemented to test out the emails at locals

## Development Setup

Prerequisites:

- PostgreSQL
- Bundler
- Node(>= 11.x)
- Yarn

```sh
bundle install
yarn install
```
Now you need to setup the database. And you need to run following commands but before running them you need to change the values of username and password of your pg inside 
```sh
config/database.yml
```
Once changed, run following commands:

```sh
rails db:create
rails data:migrate
```

Now you are all set. Run following command on your terminal:

```sh
rails server 
```
To render css and js assets faster open another tab and run following command:

```sh
./bin/webpack-dev-server
```

open browser at: [http://localhost:3000](http://localhost:3000).

Cheers!!