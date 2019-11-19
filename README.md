# README

Reference: https://guides.rubyonrails.org/getting_started.html

Getting started:
```
$ bundle init
$ bundle install --path vendor/bundle
```

If there are any issues with running ```$ bundle exec rails server```, it may be due to two things:
1. ```$ curl -o- -L https://yarnpkg.com/install.sh | bash```
2. Install Node.js

There may need updating for yarn, within the app directory:
```$ yarn install --check-files```

Then you'll have to migrate the db:
```$ bundler exec rails db:migrate```
