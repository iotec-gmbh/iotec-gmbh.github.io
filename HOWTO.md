# iotec Website

This repository contains the code for the iotec website.

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

https://127.0.0.1:4000/
