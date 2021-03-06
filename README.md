# flask_jwtlib

v0.0.3

[![Build Status](https://travis-ci.org/uchicago-library/flask_jwtlib.svg?branch=master)](https://travis-ci.org/uchicago-library/flask_jwtlib) [![Coverage Status](https://coveralls.io/repos/github/uchicago-library/flask_jwtlib/badge.svg?branch=master)](https://coveralls.io/github/uchicago-library/flask_jwtlib?branch=master) [![Documentation Status](https://readthedocs.org/projects/flask-jwtlib/badge/?version=latest)](http://flask-jwtlib.readthedocs.io/en/latest/?badge=latest)

A minimal library for working with jwts in Flask apps.

Primarily aimed at client operations - validation, authorization, and working with tokens.

[Read The Docs](https://flask-jwtlib.readthedocs.io/en/latest/)

## Note
> Those tests don't do anything, and the coverage is awful!
- Everyone, hypothetically

You're correct. However, the proof is in the pudding. I opted not to mock up a whole flask
environment to test this library with because I created it in order to abstract common
functionality out of [ipseity](https://github.com/uchicago-library/ipseity). Ipseity has tests, and
(at time of writing) 90%+ coverage, and calls (or has called) every line of code in this library.

If this changes in the future I'll write tests specifically for this library, until then I recommend
having a look at the ipseity tests and metrics.

# Author
Brian Balsamo <brian@brianbalsamo.com>
