# OH NO

```
.
├── readme.md
├── .git             # <= 1. but you did it here.
└── sample_app
    ├── Gemfile      # <= 1. You should have initiatlized in here
    ├── Gemfile.lock
    ├── README.rdoc
    ├── app
# ...
```

You can deploy to heroku with the `git subtree` command

# PHEW

```
git subtree push --prefix RAILS_DIR_NAME heroku master
```

So if my Rails app is inside a directory called "sample_app" you can run

```
git subtree push --prefix sample_app heroku master
```


