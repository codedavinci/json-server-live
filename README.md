# Deploy `json-server` to _Heroku_

### Install Heroku

1. Create an account on <br/>[https://heroku.com](https://heroku.com)
2. Install the Heroku CLI on your computer: <br/>[https://devcenter.heroku.com/articles/heroku-cli](https://devcenter.heroku.com/articles/heroku-cli)

3. Connect the Heroku CLI to your account by writing the following command in your terminal and follow the instructions on the command line:
```bash
heroku login
```


### Create the project

1 . Clone this repo

2 . Change `db.json` to your own content according to the [`json-server example`](https://github.com/typicode/json-server#example) and then `commit` your changes to git.

3 . Then create a remote heroku project, kinda like creating a git repository on GitHub. This will create a project on Heroku with a random name. If you want to name your app you have to supply your own name like `heroku create project-name`:
```bash
heroku create
```

4 . Push your app to __Heroku__ (you will see a wall of code)
```bash
git push heroku master
```

5 . Visit your newly create app by opening it via heroku:
```bash
heroku open
```

6 . For debugging if something went wrong:
```bash
heroku logs --tail
```

---

