# CouchApp: Standalone CouchDB Application Development Made Simple

CouchDB can serve web applications straight from the database. CouchApp is a set of tools and sane defaults for
creating a CouchDB application.

## What CouchApp offers

Installing CouchApp gives you a tool to create and distribute CouchDB applications. In this sense it's similar
to django or rails' command line tool.

A CouchApp is simply a set of attachments and functions that will be synced to a CouchDB design document, the 
CouchApp tool allows you to edit these as files and then /push/ them to your database.

To help you get up and running, the CouchApp tool can generate a vanilla project with some sane defaults.


### Write apps using just JavaScript and HTML

Render HTML documents using JavaScript templates run by CouchDB. You'll get parallelism and cacheability, **using only HTML and JS.** Building standalone CouchDB applications according to correct principles affords you options not found on other platforms.

### Deploy your apps to the client

CouchDB's replication means that programs running locally, can still be social. Applications control replication data-flows, so publishing messages and subscribing to other people is easy. Your users will see the benefits of the web without the hassle of requiring always-on connectivity.

## Installation

Couchapp requires Python 2.5x or sup. To install couchapp using
easy_install you must make sure you have a recent version of distribute installed:

    $ curl -O http://python-distribute.org/distribute_setup.py
    $ sudo python distribute_setup.py
    $ easy_install pip

To install or upgrade to the latest released version of couchapp:

    $ pip install couchapp

To install/upgrade development version :
   
    $ pip install http+git://github.com/couchapp/couchapp.git#egg=Couchapp

Note: some installations need to use `sudo` command beafore each command line.

To install on windows follow instructions
[here](http://www.couchapp.org/page/windows-python-installers) .

More installion options on the
[website](http://www.couchapp.org/page/installing).

## Getting started

Read the [tutorial](http://www.couchapp.org/page/getting-started).

## Other resources

* [Frequently Asked Questions](http://couchapp.org/page/faq)
* [couchapp command line usage](http://couchapp.org/page/couchapp-usage)
* [Extend couchapp command line](http://couchapp.org/page/couchapp-extend)
* [CouchApps with DesktopCouch](http://couchapp.org/page/desktopcouch)
* [List of CouchApps](http://couchapp.org/page/list-of-couchapps)
* [Video Tutorials and Screencasts](http://couchapp.org/page/videos)
* [Roadmap](http://couchapp.org/page/roadmap)
* [CouchApp Garden](http://couchapp.org/page/garden)
* [Mailing List](http://groups.google.com/group/couchapp)
* [Contributing to CouchApp](http://couchapp.org/page/how-to-contribute)
* [Some development notes](http://couchapp.org/page/development-notes)
* [Interactive Docs](http://couchapp.couchone.com/docs/_design/docs/index.html)
* [Instruction on how to install this.pages app on your own machine](http://couchapp.org/page/pages-install)

