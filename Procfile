web: sh target/bin/webapp
heroku ps:scale web=1
worker:  bundle exec rake jobs:work
