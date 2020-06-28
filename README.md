# Personal Website

This is the github repo for my personal website www.sabirotmane.com

The website is hosted on a different (private) repo but this repo contains all the main files which were made to build the website itself.
This was made using the [hugo](https://gohugo.io/) framework and built on the [Introduction](https://themes.gohugo.io/hugo-theme-introduction/) theme.

## Dependencies

To build the website, you first need to install hugo. If you're running MacOS and have `homebrew` installed then you can run the command below. Otherwise, you can refer to this [link](https://gohugo.io/getting-started/installing/) for instructions on other operating systems.

```bash
brew install hugo
```

## Building and Editing

### Build

In order to build the website - if you would like to play around with it - you have to clone this repo and then build and serve the build. You can do so by following these steps

```bash
git clone https://github.com/otmanesabir/personal-website.git
cd personal-website
hugo -themesDir .
hugo serve -themesDir . #to start the website on a local host (http://localhost:1313/)
```

### Editing

Making changes to the website is quite easy as well. You can head to the `content/eng` directory and edited the markdown files, if you're running a local host then the website will automatically rebuild and update the changes. Otherwise, you'll have to rebuild the website.

## Deploy

_This step will only work if you've setup your own repo and github page but you can use the `deploy.sh` file as a reference)._\
To deploy the changes made here to your website simply run `./deploy.sh "with an optional message"` and all the changes will be automatically sent to your page.
