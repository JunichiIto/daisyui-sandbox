# daisyui-sandbox

Sample app for daisyUI.

## Setup 

```
bin/setup
```

## Run 

``` 
bin/dev
```

Open http://localhost:3000 .

## Deploy to Heroku 

https://devcenter.heroku.com/articles/getting-started-with-rails7

```
heroku apps:create
heroku addons:create heroku-postgresql:essential-0
git push heroku main
heroku run rake db:migrate
heroku open
```

## License

MIT License
