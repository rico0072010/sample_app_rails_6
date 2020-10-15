# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
(6th Edition)
by [Michael Hartl](https://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Information

Sample application is a part of Learn Enough series of tutorials to get the basics knowledge of web development.
This App is like a twitter clone with all neccessary functionality, it has one to many association, many to many association, user and post functionality,
actions restrictions, sessions, image uploading with fog, bootstrap styling, feed and more.

(THIS VERSION OF APP WITHOUT EMAIL CONFIRMATION AND PASSWORD RESET) 

Checkout the app on heroku [Sample App Rails 6](https://my-sample-app-rails6.herokuapp.com/)

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).
