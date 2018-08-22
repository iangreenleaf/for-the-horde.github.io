# For the Horde! Online #

This is the website presence of FtH.
It's a static site built with Jekyll and hosted by GitHub.

## Running in development ##

First you'll need a current version of Ruby.

A good option is to use rbenv or rvm, either of which makes installing easy and
will detect the correct version automatically.

Once you have Ruby installed, run:

```
gem install bundler
bundle
```

Then you can run the development server with:

```
./bin/jekyll serve
```

The server will give you a local address to visit in your browser, and show
changes on page load.

## Deploying ##

Pushing to the master branch will automatically build the website to go live.
