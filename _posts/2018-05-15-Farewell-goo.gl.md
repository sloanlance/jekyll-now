---
layout: post
---

According to the "[Transitioning Google URL Shortener to Firebase Dynamic Links](https://developers.googleblog.com/2018/03/transitioning-google-url-shortener.html)" article on the Google Developers blog, the [goo.gl](goo.gl) URL shortening service is being phased out.  Some of its features were disabled on 13 April 2018 and most of the rest of the management features will be disabled on 30 March 2019.  Redirection for existing links will continue to work after that time, but it's not clear how long that will be the case.

Google is recommending people transition to their new [Firebase Dynamic Links](https://firebase.google.com/products/dynamic-links/) (FDL) service.  It's unclear whether that service can be a direct replacement for goo.gl.  At first glance, it seems to be a much more specialized service requiring development.  I plan on investigating it further and post my findings here.

I'll miss goo.gl, but in addition to trying FDL, I'll  try one of the other redirection services recommended in Google's blog post.  I suppose those services will have the benefit of allowing the target URLs to be edited.
