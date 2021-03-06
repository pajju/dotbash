# Dotbash

Dotbash is a customization of "Bash it" by [Swaroop C H](https://github.com/swaroopch).

# Bash it

**Bash it** is a mash up of my own bash commands and scripts, other bash stuff I have found. 

(And a shameless ripoff of [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh). :)

Includes autocompletion, themes, aliases, custom functions, a few stolen pieces from Steve Losh, and more.

## Install

1. Check a clone of this repo: `git clone http://github.com/swaroopch/dotbash.git ~/code/dotbash`
2. Run `~/code/dotbash/install.sh` (it automatically backs up your `~/.bash_profile`)
3. Edit your `~/.bash_profile` file in order to customize bash-it -> Do change `MY_USER_NAME` setting to your login user name.

**NOTE:**
The install script will also prompt you asking if you use [Jekyll](https://github.com/mojombo/jekyll). 
This is to set up the `.jekyllconfig` file, which stores info necessary to use the Jekyll plugin.


## Help Screens

```
bash-it (will show all the help commands)
aliases-help
rails-help
git-help
plugins-help
```

## Your Custom scripts, aliases, and functions

For custom scripts, and aliases, just create the following files (they'll be ignored by the git repo):

* `aliases/custom.aliases.bash`
* `lib/custom.bash`
* `plugins/custom.plugins.bash`

Anything in the custom directory will be ignored, with the exception of `custom/example.bash`.

## Themes

There are a few bash it themes.  If you've created your own custom prompts, I'd love it if you shared with everyone else!  Just submit a Pull Request to me (revans).

## Help out

I think everyone has their own custom scripts accumulated over time.  And so, following in the footsteps of oh-my-zsh, bash it is a framework for easily customizing your bash shell. Everyone's got a custom toolbox, so let's start making them even better, **as a community!**

Send me a pull request and I'll merge it as long as it looks good. If you change an existing command, please give an explanation why. That will help a lot when I merge your changes in. 

Thanks, and happing bashing!


## Contributors

* [List of contributors][contribute]

[contribute]: https://github.com/revans/bash-it/contributors
