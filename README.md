# Tale

[![Gem Version](https://badge.fury.io/rb/tale.svg)](https://badge.fury.io/rb/tale)

[![Build Status](https://travis-ci.com/gndclouds/11-11.svg?branch=master)](https://travis-ci.com/gndclouds/11-11)

11.11 is a journal featuring noted, invited contributors in poetry, nonfiction, fiction, fine arts, and architecture and design. 11.11 brings consequential art and writing to a global audience, interrogating the consecution of art and culture and inviting reflection on creativity in its manifest forms in the 21st century.

## Development Environment

Install on WLS

Update and Upgrade

    sudo apt-get update -y && sudo apt-get upgrade -y

Install Ruby with BrightBox Repo

    sudo apt-add-repository ppa:brightbox/ruby-ng
    sudo apt-get update
    sudo apt-get install ruby2.5 ruby2.5-dev build-essential dh-autoreconf

Update Ruby Gems

    sudo gem update

Install jekyll and bundler

    sudo gem install jekyll bundler

Check jekyll version to see if complete

    jekyll -v

If there are errors related to

    cannot load such file -- bundler

Install bundler with

    sudo gem install bundler

If still issues because of incorrect bundler version

    sudo gem install bundler:1.16.6

Then run this command 

    bundle install

Now try to check jekyll version

    jekyll -v

If errors related to publc_suffix verison

    bundle exec jekyll -v

## Launch Local Server

To launch the Jekyll web server locally

Make sure to be in the main project directory

    jekyll serve

If there are issues related to public_suffix verison

bundle exec jekyll serve