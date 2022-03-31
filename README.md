# Show off your git tricks


## Making custom aliases right in git

To define a Git alias, use the `git config` command with the alias and the command you want to substitute. For example, to create the alias `p` for `git push`:

```
$ git config --global alias.p 'push'
```

You can use an alias by providing it as an argument to `git`, just like any other command:

```
$ git p
```

To see all your aliases, list your configuration with `git config`:

```
$ git config --global -l
user.name=ricardo
user.email=ricardo@example.com
```
