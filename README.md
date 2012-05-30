truecanary
==========

The idea being that we split out all our logic for alerts when data changes.

(this request has more exceptions than it used to) -- trending calculations.

And we put it into trueminer.

You can do anything you want , put any data feed in, as long as we can convert it to a number, we'll store it in a timeseries,
and let you set alerts on it when it transitions from good / bad, etc.  Or jsut let you query for the current trending rate.

Hopefully we'll get to the place where you could use this in heroku