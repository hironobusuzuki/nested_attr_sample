# nested_attr_sample

http://ruby-rails.hatenadiary.com/entry/20141208/1418018874
$ cd nested_attr_sample/
$ bundle install --path vendor/bundle
$ bundle exec rails new --skip-bundle nested_attr_sample
$ bundle exec rails g scaffold User usaname:string age:integer
$ bundle exec rails g model Address zipcode city street tel user_id:integer
$ bundle exec rake db:migrate
$ bundle exec rails s
