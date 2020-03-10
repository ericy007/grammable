# README

Grammable is a Test Driven Post listing platform built with the purpose of working in a team environment, allowing each tester to test the code before moving forward with additional features within the app

# Objective:
An Instagram clone that we built using industry-standard, test-driven development following numerous red/green/refactor cycles.

![Screen Shot 2020-03-09 at 11 47 40 PM](https://user-images.githubusercontent.com/50501566/76277892-76ef5400-6260-11ea-9d24-64427d5a2706.png)

# Running Locally:
```
bundle install
```
Run the migration:
```
rake db:migrate
```
The application should now be running on your localhost.
# Testing
To run test suite:
```
heroku create APP_NAME
```
Now push it up to Heroku with the following command:
```
git push heroku master

```
To deploy live
```
heroku apps:info
```
Author
[Eric Yabit](https://github.com/ericy007/grammable).
