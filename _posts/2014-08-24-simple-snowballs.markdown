---
layout: post
title: Simple Snowballs 
---
Well then, not the most productive morning when I assumed this project would only take me a few hours. This seems to happen more often than I'd prefer it to.

<h2>Scenario</h2>
I decided to throw together a simple little webapp and figured why not use the Snap Framework and MongoDB. Found the two possible Snaplets for MongoDB and assumed it would be a nice few hour project. I haven't used Snap in awhile so it may take me a bit to get back up to speed but should be a fun time.

<h2>Results</h2>
Hours of cabal hell in which I was never actually able to get the MongoDB snaplets to install because of insanely specific dependencies all around and an inability to want to update the two years untouched snaplets to use a more recent version of the MongoDB packages which functionality they relied on.

<h2>What Now?</h2>
Since I was never able to get out of hell I decided to give Yesod a chance, heard great things about it so might as well jump in. The install went fairly easily with yesod-platform, had a minor hiccup with persistent-mongodb not installing right but got that one straightened out, and finally had to add the unix package to my .cabal file because it was showing up as hidden and thus Yesod couldn't start. We will see how the project turns out from here on out.


