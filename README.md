# php-login-minimal

A simple, but secure PHP login script. Uses the ultra-modern & future-proof PHP 5.5 BLOWFISH hashing/salting functions (includes the official PHP 5.3 & PHP 5.4 compatibility pack, which makes those functions available in these versions too). 

## Why does this script exist ?

In the PHP world every beginner tries to build login systems from scratch, doing all the typical mistakes, usually going from saving plain text passwords to using (horribly wrong) MD5 hashing. This script tries to give beginners a usable code base with a fully implemented user authentication ("login") system, preventing less-experienced developers at least from the worst security issues.

This script was originally part of the "php-login project", a collection of 4 different login scripts made in the 2012-2013 PHP era to give especially beginners and security-inexperienced users a set of basic auth functions that fitted the most modern password hashing standards possible. You know, this was the time when even major companies like SONY and LinkedIn used horrible outdated MD5-hashing for their passwords (or even saved everything in plain text) and when the big PHP frameworks didn't have proper user auth solution out-of-the-box.
