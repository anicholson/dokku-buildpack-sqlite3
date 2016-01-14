# dokku-buildpack-sqlite3

Small buildpack for dokku (though it may work on Heroku as well, untested) that installs SQLite3 into the app's container.

It doesn't install any bindings; it's expected that you'll use this in conjunction with another buildpack for the language/runtime you're using.