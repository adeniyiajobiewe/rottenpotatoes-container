web: bundle exec rails server -p $PORT

worker: heroku run rake db:migrate
worker: heroku run rake db:seed