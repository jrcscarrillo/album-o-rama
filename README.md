Album O'Rama
============

Phalcon PHP is a web framework delivered as a C extension providing high
performance and lower resource consumption.

This is a sample application for the Phalcon PHP Framework. We expect to
implement as many features as possible to showcase the framework and its
potential.

Please write us if you have any feedback.

Thanks.

NOTE
----
The master branch will always contain the latest stable version. If you wish
to check older versions or newer ones currently under development, please
switch to the relevant branch.

Latest stable release: >= 0.7.0

Get Started
-----------

#### Requirements

To run this application on your machine, you need at least:

* >= PHP 5.3.3
* Apache Web Server with mod rewrite enabled
* Latest Phalcon Framework extension enabled

Then you'll need to create the database and initialize schema:

    echo 'CREATE DATABASE albumorama' | mysql -u root
    unzip schemas/albumorama.sql
    cat schemas/albumorama.sql | mysql -u root albumorama