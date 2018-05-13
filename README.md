FFBW website
============================
[ffbw.de](https://ffbw.de)

## Dependencies
 - Install a javascript runtime, e.g. nodejs
 - Install bundle by running `gem install bundle`
 - Install the dependencies by running `bundle install --path vendor/bundle`

## Building
 - Use `bundle exec rake build`. This will build the website to the `_site` directory

## Serving (to work locally)
 - Use `bundle exec rake serve`. This watches files for changes and serves the website on http://0.0.0.0:4000/

## Testing
 - Use `bundle exec rake test`
State of the current master branch, powered by Travis-CI:
[![Build Status](https://travis-ci.org/ffka/karlsruhe.freifunk.net.svg?branch=master)](https://travis-ci.org/ffka/karlsruhe.freifunk.net)

