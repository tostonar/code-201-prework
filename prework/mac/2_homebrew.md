### Install Homebrew

You may already have Homebrew installed. Let's see if you do. Type

```
which brew
```

If you do not have Homebrew installed you will **not** get an error message! No message will be provided at all! Instead you will see the same prompt as before.  In that case,  we need to install Homebrew.

If Homebrew *is* installed, you will see some text like `/usr/local/bin/brew` followed by the command prompt on the next line.  

Follow below to install or skip to Update Homebrew if it is installed.

Now it's time to install <a href="http://brew.sh/" target="_blank">Homebrew</a>, the de facto package manager for OS X. If you've never heard of a package manager, think of it as an App Store of **free** command line programs.

To get started, run the following command.

```
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/install/master/install)"
```

**TIP:** Be sure to agree when asked to install the **XCode Command Line Tools**. This takes about 30 minutes to download and install on average.


### Update Homebrew

If you've previously installed Homebrew, now's a good time to update it by running the following command.

```
brew update
```

If it's been a while since the last update, you'll see something like this.

![](https://i.imgur.com/OCAX71o.png)

Otherwise, you'll see something like this.

![](https://i.imgur.com/JPB9Gnn.png)

**TIP:** Run this command periodically as Homebrew doesn't auto-update itself. :sweat:


### Verify Homebrew

To verify Homebrew is installed correctly, run the following command.

```
brew doctor
```

If Homebrew is you'll see something like this:

![](https://i.imgur.com/DWfdE3D.png)

If Homebrew is not installed, you will see something like:

`-bash: brew: command not found `

### [⇐ Previous](1_terminal.md) | [Next ⇒](3_atom.md)
