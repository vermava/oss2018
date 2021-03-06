# Open Security Summit 2018

This is the source code for the web pages in https://open-security-summit.org

The website is generated using [Hugo](https://gohugo.io). We use a theme originally based on the [Hugo Universal Theme](https://themes.gohugo.io/hugo-universal-theme/).

To contribute to this repository, you can edit simply using the GitHub integrated editor. You will need to have a [GitHub account](#github), and a new pull request with your changes will be created.

If you need to edit multiple files, or if you want to check the resulting pages before posting a pull request, you can download Hugo and use it locally. It is a simple process, and you cna check your work before submitting the changes.

# Editing locally

## You need Git and Hugo

* Install [Hugo](https://gohugo.io/getting-started/installing/)
* Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

[Fork this repo](https://github.com/OpenSecuritySummit/oss2018#fork-destination-box) first, and when cloning your copy install dependent submodules also (the Theme is in a submodule repo):

```
$ git clone --recurse-submodules https://github.com/<your github username>/oss2018.git
```

Don't forget to make it recursive, or you will have errors executing _hugo_ afterwards!

Make your changes, commit to *your* fork of the repository, and create a pull request afterwards. It is very easy to create a PR going to the GitHub Web page of your repo. You will see a "create a pull request" link, so you follow that one and do a pull request against our repository.

After we merge your changes, it will take until to 10 minutes to go live. We are in the [process of lowering this time](https://github.com/OpenSecuritySummit/oss2018/issues/167) to something more manageable.

## GitHub
* [Signup](https://github.com/) for a GitHub account
* Signin to GitHub
* Generate or locate your [SSH Key](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) and add them to your GitHub profile settings:
	profile > settings > SSH and GPG Keys

## Serving Hugo
From there, you've got all the files ready to go and you can start your hugo server to preview the changes you made. Live reload will update your change in the browser as soon as you hit that `save` key.

```
$ hugo serve -v
```

The terminal will tell you at which address your hugo server lives, but it usually is at `http://localhost:1313`

## Editors
Several editors for better markdown editing
* [Sublime](https://www.sublimetext.com/3) has package called [MarkdownExtended](https://github.com/jonschlinkert/sublime-markdown-extended) that improves Markdown + Front Matter syntax highlighting
* [Atom](https://atom.io/) has a built in GitHub Markdown syntax highlighting
* [Visual Studio](https://www.visualstudio.com)
* [WebStorm](https://www.jetbrains.com/webstorm/)

## Git Clients
Git, using command lines can be a little bit confusing at first, those UI clients will help wrap your head around it.
* [GitHub Desktop](https://desktop.github.com/)
* [Source Tree](https://www.sourcetreeapp.com/)
* [Git Kraken](https://www.gitkraken.com/)