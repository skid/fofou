# Overview

Fofou (Forums For You) is a simple forum software inspired by [Joel On Software forum software](http://discuss.joelonsoftware.com/?joel).
Original code by http://blog.kowalczyk.info/software/fofou/

I made a big refactoring of the code, fixed some bugs, and removed the RSS and email feature which I plan to rewrite.

## Installation

Fofou runs on Google App Engine infrastructure. You need to get an [App Engine](http://code.google.com/appengine/docs/gettingstarted/uploading.html) account and upload fofou.
Once installed, you can create one or more forums through the web interface.

## Deployment philosophy

Fofou isn't designed as a forum hosting platform for hosting hundreds of forums for many people.
It's designed to host a few forums for one person so the owner of App Engine account is implicitly an admin for all forums hosted from that account.

## Design philosophy

You'll quickly see that Fofou differs in many ways from most common forum software. 
There are good reasons for the differences and [Joel Spolsky describes those reason in great detail](http://www.joelonsoftware.com/articles/BuildingCommunitieswithSo.html)

## License

The original python code is written by [Krzysztof Kowalczyk](https://github.com/kjk/) and is in Public Domain.
This fork is also in the public domain.

## Contributing

Fofou is open-source so if you want to improve the code, fork away.