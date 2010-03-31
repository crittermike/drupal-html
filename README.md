Drupal Test HTML
================

INFORMATION:
-----------

In the index.html file, you'll find a bunch of HTML to be used to 
test your Drupal theme. It includes both regular old HTML elements
and Drupal-specific elements (such as tabs and status messages)

USAGE:
------

Just copy and paste everything in the index.html file into a node,
such as a page. The index.html purposely isn't a full HTML file 
(e.g., there is no <head>) so that the entire file can be copied
into the node and still validate.

Then just view the node.

FAQs:
-------

**Why is this useful?**

It's pretty common for developers to send out a fresh new site to the
client, then a couple weeks later discover that the site looks horrible
because not all possible types of content have been accounted for. This 
is especially dangerous when WYSIWYGs are in use.

This should fix that.

**Isn't it stupid to test the style of stuff like tabs and status messages
in the theme's content section instead of the header?**

Well, yes and no. Yes, it's true that tabs and status messages probably
won't ever me in the same div as the content itself, but it's still good
to test it there to ensure that everything looks good no matter where it
is. If tabs are only styled to look good in the header, for example, then 
they'll look like crap when moved somewhere else.

**Is this useful for custom themes as well, or just for general purpose
themes which will be open sourced?**

Sure, it's useful for everything. If a theme is for a custom site, then 
you have your client, and if a theme is for Drupal.org, then anyone who
downloads it is your "client", and their way, the client can screw up the
styles if it hasn't been thorougly tested.
