web: gunicorn smstoemailreply
heroku ps:scale web=1
worker:  bundle exec rake jobs:work
heroku ps:scale worker=1
gem rails_autoscale_agent
