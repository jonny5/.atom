# .atom dotfiles

A collection of my Atom dotfiles. I recommend placing this .atom directory in your home directory as well for easier editing/pushing to github (see installation section below:)

### Installation

```sh
# add this repo to your existing `.atom` directory
cd  ~/.atom
git init
git remote add origin git@github.com:Lordnibbler/.atom.git

# bring yourself up to date
git fetch

# blow away your config
git reset origin/master --hard

# OR pull in my config and resolve conflicts
git pull origin/master
```

### Updating
In the future, you can simply `git pull` and resolve conflicts between machines if needed.
