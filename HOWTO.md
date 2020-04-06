# iotec Website

This repository contains the code for the iotec website.

## Contribute

If you would like to work on this website you should
look at the file `_config.yml` first.
This is where the content of the landing page is configured.
If you want to change images, you can find them in the `images` folder.
You can also add markdown files to the root folder, who will appear as separate pages
that can be navigated to from the right hand folding menu.

## Build the Page Locally

To build this page locally, you need to have jekyll installed.

### Install Jekyll

On ubuntu you need the following pre-requisites:

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
```

You can then install Jekyll with:

```bash
gem install jekyll bundler
```

You might need to run this command with `sudo`, or,
[set up a path in your home folder to install to](https://jekyllrb.com/docs/installation/ubuntu/).

### Build Page

Go to the folder that contains this repository.
You probably need to install the dependencies of the website first.
You can simply do this with this command:

```bash
bundle install
```

Afterwards you should be able to serve the page to your localhost like this:

```bash
bundle exec jekyll serve
```

Usually you can then open the page in your browser under:

<https://127.0.0.1:4000/>
