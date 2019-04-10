# Sample app for practising ruby

This is a sample app to learn developing a twitter like web app with ruby on rails. It is developed taking help from railstutorial.org/book. The user model has been implemented and login, signup form are working. The user profile editting is also working. This app also includes suoeruser giving administrative rights to delete any user. Microposts and following oher users features are still to be deployed.

## Getting started

To run the app on localhost, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate 
```

If sample users are required for testng:

```
$ rails db:seed
```


Finally, run the tests to verify that everything is working correctly:

```
$ rails test
```

If the test passes, you'll be ready to run the app in a local server:

```
$ rails server
```
