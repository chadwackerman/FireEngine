----------------------------------------------------
FireEngine - Google AppEngine Extensions for Firebug
----------------------------------------------------

In AppEngine 1.2.4 Google added per-request detailed cost and cpu timing information.

When you're logged in as Admin and access your application, Google sends informative headers:
http://googleappengine.blogspot.com/2009/08/new-features-in-124.html

I hacked display of these headers into the Net panel in Firebug.

SCREENSHOT:
http://cloud.github.com/downloads/chadwackerman/FireEngine/screenshot.gif

- - -

Ideally this needs to be packaged as a Firebug extension.  For now:

Right click and save the Firebug 1.4.3 package:
https://addons.mozilla.org/en-US/firefox/downloads/latest/1843/addon-1843-latest.xpi

Rename the .xpi to .zip, extract the files, and replace content/firebug/net.js with the new one.

If someone would like to package this up properly, I'll promptly update this.
Thank you!

