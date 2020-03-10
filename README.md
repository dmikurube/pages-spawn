GitHub Pages Playground
========================

https://pages.github.com/versions/

Set up (macOS)
---------------

```
brew update && brew upgrade ruby-build
env RUBY_CONFIGURE_OPTS="--with-openssl-dir=/usr/local/opt/openssl" rbenv install 2.5.3  # Set up Ruby
(rbenv local 2.5.3)
(gem install bundler)
bundle install --path vendor/bundle
```
