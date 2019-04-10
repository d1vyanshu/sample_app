## Getting started

To run the app on localhost, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the tests to verify that everything is working correctly:

```
$ rails test
```

If the test passes, you'll be ready to run the app in a local server:

```
$ rails server
```
