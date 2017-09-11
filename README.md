# New Computer Checklist
Welcome to Tommy John! Let's get your computer set up:

## Install Git
First we need to install git for version control.
[Git Installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Install Slack
Our team uses slack to communicate, so install slack onto your computer, and we recommend you install the slack app onto your mobile device as well. Go to [Tommy John's Slack Page](https://tjhq.slack.com) to set up an account with your Tommy John email address.

## Install NVM
Some projects will require to run with an older version of node, so we will need NVM to switch between versions.
The best way to install would be to run the following command into your terminal or command prompt:
```shell
curl https://raw.githubusercontent.com/creationix/nvm/v0.30.2/install.sh | bash
```
The version of Node we will be using for Project Sail is 4.4.0, so use to following command to install it:

```shell
nvm install 4.4.0
```

## Create Github account for Tommy John Work
Make a Github account specifically for the work you will be doing here at Tommy John and send your mentor or team leader the username to be given access to your relevant project repositories. You may want to [set up your SSH keys](https://help.github.com/articles/connecting-to-github-with-ssh/) to optimize your git workflow on your machine!

## Install Coding Environment
Install your text editor, terminal, config files, and/or any other tools you will need for your coding workflow. Some viable options for a text editor include [Visual Studio Code](https://code.visualstudio.com/), [Atom](https://atom.io), [Sublime Text](https://www.sublimetext.com/).

Some tools our devs have found useful include [iTerm](https://www.iterm2.com/) for streamlined terminal input, [nGrok](https://ngrok.com/) for local server tunneling to simplify mobile device testing, and [Emmet](https://emmet.io/) for faster markup coding.

#### VIM
It is a good idea to get acquainted with VIM, not only for its optimized performance as compared to more bloated code editors like Atom or Code, but also to allow for more elaborate git commit messages across multiple lines, which will be required for certain workflows. A built in tutorial for VIM is included in MacOS terminal by running the command ```vimtutor```.

## Install Stencil
We will be using [Stencil](https://stencil.bigcommerce.com/), a BigCommerce framework, to work on project Sails. The following steps are required to install Stencil:
1. ```npm install -g stencil```
2. ```npm install -g @bigcommerce/stencil-cli```
3. Get your stencil configured with your own Client ID, Access token, and the link to the store API from your team leader.
4. ```stencil start``` and you're ready to roll!

## Useful Bookmarks
* [Tommy John Style Guide](https://staging.tommyjohn.com/style-guide) - for reference to official Tommy John Styles including colors and HTML element styling
* [Stencil Docs](https://stencil.bigcommerce.com/docs) - documentation for Stencil framework on BigCommerce website
* [Sass Style Guide](https://github.com/bigcommerce/sass-style-guide) - BigCommerce style guide for Sass
* [Front-end Developer Handbook 2017](https://www.gitbook.com/book/frontendmasters/front-end-handbook-2017/details) - Useful reference for Frontend Devs in 2017, made by Frontend Masters
* [Emmet Cheatsheet](https://docs.emmet.io/cheatsheet-a5.pdf) - cheat sheet for Emmet toolkit for faster markup coding
