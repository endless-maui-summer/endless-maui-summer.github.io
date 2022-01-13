https://jekyllrb.com/

```
gem install bundler jekyll

```

> if you get an openssl error, may need to pass cpp flags, for example

```
brew update && brew install openssl
gem install eventmachine -- --with-cppflags="-I/usr/local/opt/openssl@3/include"
```

> note the version, ensure it matches installed version

## install dependencies

`bundle install`

`bundle exec jekyll build`

`bundle exec jekyll serve`
