root-relative-urls
==================

Please note, that I am not supporting this pluggin. I have a copy of it here that I have made minor
modifications to because I needed those modifications and is seems that the original author is no
longer supporting the work.

The fixes I make here are mostly to allow me to continue using it.

The original plugin is located here: https://wordpress.org/plugins/root-relative-urls/

If you need changes to this plugin please feel free to fork this repo and make modifications. 
I will probably even take and pull requests.

This version contains various hacks and fixes to work around some of the issues reported on the support forum there
that I needed in order to make it work.

To ba completely honnest, I no longer use this plugin and I'm only keeping a copy of it just in case I
find it usefull in the future. I originally used it because it helped with moving a site from a dev
domain to a live domain. I have since deiscovered that if I put the two lines of code below into my
wp-config.php file that the need of this plugin for that purpose what removed.

```
define('WP_HOME', 'http://' . $_SERVER['HTTP_HOST']);
define('WP_SITEURL', 'http://' . $_SERVER['HTTP_HOST']);
```
