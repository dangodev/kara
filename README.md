Kara v1.0
===============

Ultralight blank WordPress theme

Description
-----------
This is intended for medium to advanced WordPress developers that plan on styling their website from scratch.

This is about as bare-bones as you can get in WordPress. Contains ''no CSS resets,'' ''no object-oriented BS,'' and contains only minimal styling, HTML, and WP functionality. I also removed the template comments on the assumption you know what `if:` and `elseif:` mean.

'Kara', meaning “empty” or “void” in Japanese, is something I’ve developed after spending years working with WordPress’s template system. Every site I build basically comes from this code base, though this is the first time I’ve standardized it. Every line was hand-crafted with full knowledge of what it does. Many CSS classes and containers were removed; some were left behind only as a starting example.

You’ll notice that there is no `archive.php` (or any related pages such as `tag.php`) because I usually find it superfluous to use another view from the primary `index.php` blogroll. For categories, etc. I usually just use the `.active-cat` class in the sidebar to indicate category pages. In cases of extreme need, an [`is_archive()](//codex.wordpress.org/Function_Reference/is_archive) conditional can be placed inside of `header.php` to add a title, etc.

This template may require some additional functions to get running based on preference, but overall was designed to omit everything possible that would end up going to waste. Included is Ryan Fait’s immaculate [sticky footer](//ryanfait.com/sticky-footer/), but if you’re familiar with this code you’d know it’s only a few additional lines to the CSS and is incredibly paradigmatic.

Compatibility
-------------
* 3.5.x
* 3.4.x
* 3.3.x

Features
--------
* Hand-crafted HTML5-validated goodness
* Cleaned-up comment template
* Minimal `functions.php` file that cleans up the WP head and contains CPT starter code
* No ridiculous `include` file or self-righteous PHP template class for you to decipher
* No CSS resets
* Only 6 starting lines of CSS
* Fewer than 10 starting IDs / classes

Includes
--------
This plugin doesn’t include any libraries whatsoever, or make any assumptions as to how you code. However, it is set up to:

* Implement Ryan Fait’s [sticky footer](//ryanfait.com/sticky-footer/)
* Set jQuery v2.0 to Google CDN (only because most plugins end up attaching their own jQuery version anyway)

Download
--------
https://github.com/dangodev/Kara/zipball/master