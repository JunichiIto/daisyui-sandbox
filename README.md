# daisyui-sandbox

Sample app for daisyUI.

![Screenshot 2024-06-10 at 9 31 51](https://github.com/JunichiIto/daisyui-sandbox/assets/1148320/d0b24081-53db-4fee-9e63-6687165ae73a)

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
