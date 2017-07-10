web: gunicorn app:app
heroku ps:scale web=1
worker:  bundle exec rake jobs:work
