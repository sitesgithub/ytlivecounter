# Note: The code is written in Javascript along with HTML and CSS.

You need some Youtube API Keys. I have gotten some from debugging http://livecounts.net.

After you get your API keys, place all of them in a file called "keys" without quotation marks

It only has to be the keys, no quotation marks or ticks.

For a working version, click [me!](https://sitesgithub.github.io/ytlivecounter/)

Note: This does not work if you download it, then open it. You need a [webserver](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb) to do so.

What this software does is get the keys, checks if it works and uses that key to send GET requests to Google API servers to get the account the user is requesting and changes the innerText amount to the subscriberCount variable listed in the JSON from the response from the GET request every 2 seconds.
