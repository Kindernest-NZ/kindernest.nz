# Website of the Kindernest playgroup

## Build

The build requires `bundler` to manage the dependencies.

First install the dependencies:

    bundle config set --local path 'vendor/bundle'
    bundle install

The static site can then be built with `jekyll`:

    bundle exec jekyll clean
    bundle exec jekyll build
