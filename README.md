# git-hub

No login GitHub command line helper.

Just for the simple things.

## Usage

NOTE: you can use `git-hub` or enjoy git's command magic and simply use `git hub` once it is in your path.

First config your username in your global git config:

```
git config --global --set github.user <username>
```

Then you can list your repos:

```
git-hub repo list
```

Create a new repo:

```
git-hub repo new [repo]
```

The repo argument will default to the current directory.

It is easy to attach to a GitHub repo with:

```
git-hub repo upstream [repo]
```

This will automatically get called if you confirm after a `new`.

To clone all of your repos into one directory run:

```
git-hub repo clone-all
```
