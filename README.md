A quick and dirty example of how to use the hashchange event to drive your Single Page Web Application.  

This is the bare bones implementation and does not go into the details of how to set up your application
to use the hashchange event to drive page state and events, for more details on that check out our
book Single Page Web Applications: JavaScript End to End on my blog, jsjoshing.com.

In the code the changing hash tag pushes the page to update the div with the contents of the hash.  Notice
that the back button works, the forward button works, bookmarking works, and emailing or chatting the
url works.  This was a huge "aha!" moment for me when I learned it, I still think it is rampant badassery.