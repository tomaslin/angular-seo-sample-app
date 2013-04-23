to deploy

yeoman build
cd dist
git init
git add .
git commit -am "deployment"
heroku create yourappname
git push heroku master
