web: gunicorn gettingstarted.wsgi --log-file -heroku ps:scale web=1
heroku ps:scale worker=1
gem rails_autoscale_agent
worker
