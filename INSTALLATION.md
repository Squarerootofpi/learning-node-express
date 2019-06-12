## Installing Node.js

If you are using cloud9, npm will be installed for you.  If not, then you should use one of these methods to install npm.

## Installing via nmv
My preferred way to install node is to use
[nvm](https://github.com/creationix/nvm). This lets you install
multiple versions of node simultaneously, in case different apps need
different versions. I don't usually need this, but I prefer nvm
because it makes it easy for me to always get the latest stable
versions of node and npm. It also installs into my local directory,
rather than polluting the globally installed packages.

**If you are on a Mac, be sure to first do this:**

```
touch ~/.bash_profile
```

To install nvm, visit the [nvm](https://github.com/creationix/nvm)
web page and copy installation command that uses curl so you can have
the latest version. For example:

```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
```

Then close your terminal, open a new one, and type:

```
nvm install stable
nvm use stable
```

You'll now be using the latest stable versions of node and npm. You
will need to repeat `nvm use` each time you open a terminal.

## Installing via a direct download

If you prefer, you can install Node.js by [directly downloading a package](https://nodejs.org/en/download/).

## Installing via package manager

If you prefer, you can install using your package manager. If you have
Ubuntu, you can do this:


```
sudo apt-get install nodejs
sudo apt-get install npm
```

For Mac OS, you could use [HomeBrew](https://brew.sh/): [Install Node.js and npm using Homebrew on OS X and macOS](https://changelog.com/posts/install-node-js-with-homebrew-on-os-x).

