# Javascript-Injection

This example shows how to inject our local extension's kbase.js into the YouTube webpage and replace the Internet version of base.js.
This allows us to make edits to remove ads from YouTube.
This is useful to not have to buy Fiddler or to not have to use the less than reliable MITMProxy code.
In kbase.js you can search for the string KMAN to see the minor changes made to YouTube's base.js source code  to remove ads from video playback.

Note: base.js will not be replaced unless you first delete the www.youtube.com cookies and hit refresh after loading the Chrome extension.

This is a Chrome/Canary/Edge extension and can be installed by following "install chrome extension developer mode".

You will need to download and save (using the F12 tool) the original base.js from YouTube and then apply the minor edits to that file. 
Rename it kbase.js and verify by looking at the console.log statements that the extension is running and verify using the network tab that base.js 
gets redirected to the local file kbase.js.

Be careful if you Javascript Pretty Print their original base.js file, since doing this introduces errors into the code that will need to be fixed.





