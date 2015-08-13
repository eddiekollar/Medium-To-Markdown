### Medium-To-Markdown

    import-medium.py [OPTIONS] <medium post url>
       --pelican        Print out in a format suitable for publishing with the Pelican static site generator

Given a link to a post on Medium, print out a Markdown version of the post.

v0.4

* Fixed bug where script failed on some encoded ascii chars (\x<ascii hex>)


v0.3

* Embedded image support

v0.2

* Fancy quotes are now preserved

v0.1

* Basic formatting
* Links
* Block quotes
