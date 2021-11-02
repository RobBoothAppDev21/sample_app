# Ruby on Rails Tuotrial sample application

This is the sample application for 
[*Ruby on Rails Turorial:
Learn Web Development with Rails*](https://railstutorial.org/)
(6th edition)
by [Micheal Hartl](https://www.michaealhartl.com/)

## License

All sourec code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is avialable jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details

## Getting started

To get started with the app, clone the repor and the install the needed gems:

'''
$ gem install bundler -v 2.2.17
$ bundle _2.2.17_ config set --local withouth 'production'
$ bundle _2.2.17 install
'''

Next, migrate the database:

'''
$ rails db:migrate
'''

Finally, run the test suite to verify that everything is working correctly:

'''
$ rails test

If the test suite passes, you'll be ready to run the app in a local server:

'''
$ rails server
'''

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book)