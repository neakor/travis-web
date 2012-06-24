## Goals

See https://gist.github.com/e4728d00bfd1d6559f4a

### Running the app

This is a static html/js app so you shouldn't need to install anything.

    git clone git://github.com/svenfuchs/travis-ember.git
    cd travis-ember
    open public/index.html

### Compiling assets manually

    bundle install
    bundle exec rakep

### Compiling assets on change

    bundle install
    bundle exec guard
