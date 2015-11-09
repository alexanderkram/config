# Config

**Config** is a basic checklist I follow to set up a new Mac's development environment. It gets me up to speed with Bower, Git, Ruby, Node and more so I can more quickly get back to coding.

## Contents

| File | Description |
| --- | --- |
| `.bash-profile` | Customizes the Terminal.app prompt and echos the currently checked out Git branch. |
| `.gitconfig` | Global Git configuration to specify my name and email, shortcuts, colors, and more. |

## Checklist

### 1. Prep OS X

- Download and install latest version of [Xcode](https://developer.apple.com/xcode/) from the Mac App Store
- Download and install Xcode command line tools
  - `$ xcode-select --install`
- Download and install [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
- Download and install [Vagrant](http://www.vagrantup.com/downloads.html)
- Download and install [Git](http://git-scm.com/downloads)

### 2. Apps for my workflow

- [Evernote](https://evernote.com) *Save your ideas*
- [GoogleDrive](https://www.google.com/drive/) *Sync your files*
- [Slack](https://slack.com) *Communicate better*
- [Toggl](https://www.toggl.com/) *Track your time*
- [Trello](https://trello.com/) *Manage your work*

### 3. Download dependencies

- Install [homebrew](https://github.com/Homebrew/homebrew)
  - `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- Install Node
  - `$ brew install node`
- Install npm Packages:
  - `$ npm install -g gulp bower eslint`
- Install [Curl](http://brewformulas.org/Curl)
  - `$ brew install curl`
- Install [RVM](https://rvm.io/)
  - `$ \curl -sSL https://get.rvm.io | bash -s stable`
  - Install [Ruby](https://www.ruby-lang.org/)
    - `$ rvm install 2.1`
    - `$ rvm use 2.1 --default`
- Install [PHP](http://www.php.net/)
  - `$ brew install homebrew/php/php55`

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
  - [atom-beautify](https://atom.io/packages/atom-beautify)
  - [color-picker](https://atom.io/packages/color-picker)
  - [file-icons](https://atom.io/packages/file-icons)
  - [linter](https://atom.io/packages/linter)
  - [linter-eslint](https://atom.io/packages/linter-eslint)
  - [linter-less](https://atom.io/packages/linter-less)
  - [linter-phpcs](https://atom.io/packages/linter-phpcs)
  - [linter-ruby](https://atom.io/packages/linter-ruby)
  - [linter-scss-lint](https://atom.io/packages/linter-scss-lint)
