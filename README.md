# Config

**Config** is a basic checklist I follow to set up a new Mac's development environment. It gets me up to speed with Git, Ruby, GitHub, Rails, Node, and more so I can more quickly get back to coding. (Just saw this by [mdo](https://github.com/mdo) and created my own one)

## Contents

| File | Description |
| --- | --- |
| `.bash-profile` | Customizes the Terminal.app prompt and echos the currently checked out Git branch. |
| `.gitconfig` | Global Git configuration to specify my name and email, shortcuts, colors, and more. |

## Checklist

### 1. Prep OS X

- Download and install latest version of Xcode from the Mac App Store
- Download and install Xcode command line tools

### 2. Apps for my workflow

- [Evernote](https://evernote.com) *Save your ideas*
- [GoogleDrive](https://www.google.com/drive/) *Sync your files*
- [Slack](https://slack.com) *Communicate better*
- [Toggl](https://www.toggl.com/) *Track your time*
- [Trello](https://trello.com/) *Manage your work*

### 3. Download dependencies

- Install [homebrew](https://github.com/Homebrew/homebrew)
  `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- Install [rbenv](https://github.com/sstephenson/rbenv) over `$ brew install rbenv` `$ brew install ruby-build`
- Install [a Ruby version](https://github.com/sstephenson/rbenv#installing-ruby-versions) (latest version)
  - Set a [global Ruby version](https://github.com/sstephenson/rbenv#rbenv-global)
- Install common gems: `$ gem install rails sass`
- Install Node `$ brew install node`
- Install Gulp and Bower: `$ npm install -g gulp bower`

### 4. Secure Git(Hub) access

- [Generate new SSH key](https://help.github.com/articles/generating-ssh-keys/)
- [Generate an access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) for Terminal to auth your GitHub account when 2FA is enabled

### 5. Prep Terminal.app

- Load [`.bash_profile`](/.bash_profile)
- Load [`.gitconfig`](/.gitconfig) contents into the global `~/.gitconfig`
- Download and install the [Ocean theme](https://github.com/mdo/ocean-terminal)

### 6. Download Atom and Tweak it right

- Install Atom itself
- Add [Spacegray UI theme](https://atom.io/themes/spacegray-dark-ui) and [Ocean Dark color scheme](https://atom.io/themes/base16-ocean-dark-syntax)
- Enable `atom` Terminal commands: from Atom.app, open the Atom menu and select *Install Shell Commands*
- Change on Package 'tabs' to Preview Mode
- Install Packages
  - [color-picker](https://atom.io/packages/color-picker)
  - [file-icons](https://atom.io/packages/file-icons)
  - [language-jade](https://atom.io/packages/language-jade)
  - [linter](https://atom.io/packages/linter)

## Use it yourself

Fork this repo, or just copy-paste things you need, and make it your own. **Please be sure to change your `.gitconfig` name and email address though!**

## Works on my machine

Yup, it does. Hopefully it does on yours as well, but please don't hate me if it doesn't.

<3
