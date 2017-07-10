web: gunicorn app:app
heroku ps:scale web=2
worker:  bundle exec rake jobs:work
