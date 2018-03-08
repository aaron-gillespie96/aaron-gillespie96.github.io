---
layout: post
title: Some updates from February!
---
Over the last few weeks we have been developing our technical delivery for our final year project. In this
blog I am going to outline the tasks I have completed so far towards the technical delivery. Evan has been working on
the front end of the website so I have been focusing most of my effort on the back end.

Domain Name
---------------

To begin the building of the back end I first purchased a domain name from www.namecheap.com. We were unable to buy icohub.com so we
instead decided on using icohub.eu


Server hosting
---------------

We analysed different options for our website hosting but decided the most scalable and cost effective solution would be to use Amazon
AWS to host our website. I at first experimented using Amazon S3 but soon realised that this only allowed me to host a static website that had support for HTML,CSS and javascript it did not allow for the use of databases or php.


My solution was to use Amazon Lightsale. On this I deployed an Ubuntu virtual machine with a LAMP stack (linux,apache,mysql,php).
This virtual machine will host our website. I also installed a front end to the database called phpMyAdmin this allows us to modify our database from the web browser.

I then updated the nameservers so that we could access the website from our new domain name. A test version of our website is now live on

icohub.eu


My next task is to get information stored in our database and have it presented on the front-end
