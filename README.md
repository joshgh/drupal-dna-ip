# DNA

#### Display a matched strand for a given strand of DNA, 2016 December 16

#### By Josh Huffman

## Description

This is a website built in Drupal which demonstrates AJAX and testing with simpletest. It includes an ajax_articles module which displays an article using ajax when its title is clicked and a dna module which allows a user to input one half of a DNA strand and it will return the matching half.  Unit and functional tests are included with the DNA module.

## Setup/Installation Requirements

Must have a web server running with MySQL and PHP installed. This installation varies across systems, one option is to use MAMP or WAMP, instructions are available at [learnhowtoprogram](https://www.learnhowtoprogram.com/drupal/getting-started-with-drupal/server-and-database-setup).

Make sure you have git installed on your computer.
Run `git clone https://github.com/joshgh/drupal-dna-ip`

Import the database dump located in drupal-dna-ip/sites/db-backup to your mysql server, the easiest method is using phpmyadmin.

Create a mysql user with access to this database, the current site configuration uses username:dna/ password:dna

If your mysql server uses a port other than 8889 make sure to change that in drupal-dna-ip/sites/default/settings.php

Start your webserver with the document root pointing to drupal-dna-ip

Visit localhost in your browser, if the server uses a port other than 80 make sure to specify that in the URL (localhost:portnumber)

Site admin account is username:dna/ password:dna

## Support and contact details

Contact me at j.m.huffman@gmail.com with any comments or questions.

## Technologies Used

This site was build using Drupal.

### License

MIT License

Copyright (c) 2016 **Josh Huffman**
