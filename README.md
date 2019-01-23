# Javascript JSON API example: Flickr

Get an API key from Flickr at the documentation link below.

[Documentation](https://www.flickr.com/services/api/)  
[Photo Source URLs](https://www.flickr.com/services/api/misc.urls.html)

Thos example code uses JavaScript "fetch", which is more up-to-date than the Ajax requests made in the Wikipedia examples, and which you'll see in older code on the web. Read more on [JS Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API).


## Images size suffixes

See the end of line 35 and replace the "q" in "_q.jpg" with one of the following:

- s	small square 75x75  
- q	large square 150x150  
- t	thumbnail, 100 on longest side  
- m	small, 240 on longest side  
- n	small, 320 on longest side  
- \-	medium, 500 on longest side  
- z	medium 640, 640 on longest side  
- c	medium 800, 800 on longest side†  
- b	large, 1024 on longest side*  
- h	large 1600, 1600 on longest side†  
- k	large 2048, 2048 on longest side†  
- o	original image, either a jpg, gif or png, depending on source format
