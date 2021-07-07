### Install Git

Using APT, you can also install <a href="http://git-scm.com/" target="_blank">Git</a>, the version control system of choice among choosy developers.

Version control systems let programmers share and collaborate on code. With Git, multiple programmers can work on the same files, and Git keeps track of who made what changes, when. Git is usually used with a website, GitHub, that stores code (in "repositories") and lets programmers review and discuss changes before they are added. In short, Git makes everyone's lives easier.

To get started, run the following command.

```
sudo apt-get install -y git
```

Once it finishes, run the following command.

```
git --version
```

And you'll see something like this.

![](https://i.imgur.com/YmUQzF0.png)

### Git Config

Like artists, programmers sign their work. Let's configure Git to sign your commits with your name and email address.

Make sure you sign up for an account at Github <a href="https://github.com" target="_blank">here</a>.

**WARNING:** Before running the following commands, replace `YOUR FULL NAME` and `YOUR EMAIL ADDRESS` with the name and email from <a href="https://github.com/settings/profile" target="_blank">your GitHub account</a>.

```
git config --global user.name 'YOUR FULL NAME'
git config --global user.email 'YOUR EMAIL ADDRESS'
```

The terminal does not send success messages, in order to double check that you have successfully assigned your username and email:

```
git config --list
```

Your terminal should output the following lines:

```
user.email='YOUR EMAIL ADDRESS'
user.name='YOUR FULL NAME'
```

Next, run this command to download and install some awesome colors and handy aliases for Git.

```
curl -fsSL http://git.io/7UHtNA | sh
```

We'll go over these later. For now, relish in your victory of making it this far in the setup guide. :tada:

### GitHub

You're on the home stretch now! :racehorse:

Run the following command to download and install some extra Git configs that'll make your life easier when using GitHub from the command line.


```
curl -fsSL http://git.io/Ggdljw | sh
```

### Congratulations!

### [⇐ Previous](3_vscode.md) | [Next ⇒](5_node.md)