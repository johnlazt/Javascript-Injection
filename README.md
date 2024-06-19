# Javascript-Injection

This example shows how to inject our local extension's kbase.js into the YouTube webpage and replace the Internet version of base.js.
This allows us to make edits to remove ads from YouTube.
This is useful to not have to buy Fiddler or to not have to use the less than reliable MITMProxy code.
In kbase.js you can search for the string KMAN to see the minor changes made to YouTube source to remove ads from video playback.

Note: base.js will not be replaced unless you first delete the www.youtube.com cookies.

This is a Chrome/Canary/Edge extension and can be installed by following "install chrome extension developer mode".




