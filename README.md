Django blog from chapters 4, 5, and 6 of [Django for Beginners](https://djangoforbeginners.com/introduction/)

# Run locally

1. Activate the virtual environment

```sh
. .venv/bin/activate
```

2. Start the local server

```sh
python manage.py runserver
```

# Deploy

This app includes configurations for Heroku. Creating a [Heroku account](https://dashboard.heroku.com/) and setting up [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) is up to you.

1. Push the latest code to heroku

```sh
git push heroku main
```

2. Spin up the dyno (if it's not already) to serve your app

```sh
heroku ps:scale web=1
```
