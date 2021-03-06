# RailsBricks

_Create **Rails** apps. **Faster**._

**[Watch the video!](https://vimeo.com/110340717)**

---
- Title: RailsBricks
- Version: 3.7.0
- Author: Nico Schuele (www.nicoschuele.com)
- Github: https://github.com/nicoschuele/railsbricks
- Twitter: @nicoschuele

---

## Not Maintained Anymore!

**Please note that RailsBricks is currently not maintained and will likely not be upgraded to use Rails 5+. I leave it here for legacy purpose. If you want to take over, [contact me](https://twitter.com/nicoschuele).**


## Features

* replaces the `rails new` command with `rbricks -n`
* includes useful gems and sets them up for you
* offers different UI choices for your web app
* creates and configures a Devise authentication scheme
* adds the necessary resources for a blog, contact form, and more
* builds an admin zone
* configures your mailers
* inits local and remote git repositories
* ...and much more to boost your productivity!

## Prerequisites

In order to use RailsBricks, you need the following:

* A nix-based OS. That can be any flavour of Linux or OS X
* Ruby (version 2.0+)
* Some knowledge of Rails (!)

## What about Windows?

**RailsBricks doesn't run out of the box on Windows**. You will first need to install the [DevKit](http://rubyinstaller.org/downloads/) as well as the [tzinfo-data](https://github.com/tzinfo/tzinfo-data) gem.

## Ruby support

RailsBricks generates Rails apps with support for the current major Ruby release (currently, 2.0.0) + the current point release and the previous one, for example 2.2.2 & 2.2.3. If you need to use another version of Ruby, you will have to manually edit the Gemfile after the app gets created and update the following line with your chosen version number:

`ruby '2.1.5'`

## Install

Like any other gem, you simply issue `gem install railsbricks`

**Notice:** If you still have RailsBricks 1.x installed, remove it manually *before* installing RailsBricks 3.x

## Usage

To create a new app, just type `rbricks --new` and follow the wizard.

There's a great RailsBricks tutorial available on SitePoint if you want to know more: [sitepoint.com/railsbricks-start-faster-rails](https://www.sitepoint.com/railsbricks-start-faster-rails/).

## Contribute

RailsBricks is currently not maintained and not accepting pull requests anymore. If you want to take over, [contact me](https://twitter.com/nicoschuele).


## Acknowledgements

* [Nikkau](https://github.com/Nikkau), for showing me how to segregate gems without using RVM
* [Joelle Gobbo](http://ch.linkedin.com/pub/joelle-gobbo/32/4b5/a9b), for the elegant snippet used to generate a valid Rails app name
* [Jim Meyer](https://github.com/purp), for forking RailsBricks and creating an alternative version I also use
* [David Hsu](https://github.com/dvdhsu), for adding a new Brick: Devise authentication using only an email address
* the authors of the many gems used by RailsBricks
* the [Geneva.rb](http://www.meetup.com/genevarb/) Meetup Group for the beer!
* David Camarena for producing a [fork](https://github.com/athalas/railsbricks) with support for MySQL
* [Felix Wolfsteller](https://github.com/fwolfst) for doing a bit of cleanup
* everyone who emailed me, gave feedback, opened an issue on Github, submitted a pull request, tweeted, etc. I truly love the Rails community.

## License

Released under GNU GPL-3. Copyright (c) 2014-2017 Nico Schuele. See LICENSE.txt for further details.
