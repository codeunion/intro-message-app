# CodeUnion Message of the Day Applicatin

This is a basic web application written in Ruby using the
[Sinatra web framework](http://www.sinatrarb.com/).  It's meant to illustrate
a few of the key concepts that make web applications different than the
standalone programs or HTML pages you're used to writing.

## Core Ideas

The Message of the Day app is meant to illustrate two critical ideas:

1.  How a web application can interact with information available to the
    application but not directly available to the person using a browser.
2.  The idea of _persistance_, i.e., how a web application can store
    information so that it's available for future requests.

## What to Build

Once you have the application running (see below), click the various links
on the homepage.  Look at the `message-of-the-day.txt` and `quotes.txt` files.
Try to understand how the web application's behavior changes when you edit
these files.

Open `message-app.rb` in your editor of choice.  Try to figure out which parts
of the page you're looking at correspond to which pieces of code in
`message-app.rb`.  It helps a lot to have the browser and code open side-by-side
so that you can look at both simultaneously.

Your goal is to make the web application do something — _anything_ — different
than what it does when you first run it.  This can involve anything from
adding new pages to adding new behavior to a particular page.

## Running the Application

### Installing the Required Dependencies

Before you run this application, you have to install the libraries it requires
to do its work (these are specified in the `Gemfile`).  To do this, run

```shell-session
$ bundle install --without production
```

This will ensure you've installed all the libraries required to run the
application.  **Note**: you only have to run this command _once_.

### Launching the Web Application

Next, run the following command:

```shell-session
$ ruby message-app.rb
```

To stop your application, press `Ctrl+c`.  That's "Control" plus the "c" key.
