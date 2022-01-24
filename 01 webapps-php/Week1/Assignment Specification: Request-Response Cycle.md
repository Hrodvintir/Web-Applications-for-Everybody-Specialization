# Assignment Specification: Request-Response Cycle

In this next assignment, you are to retrieve the following document in a browser tab with "Developer Mode" enabled so you can examine the HTTP Response headers. You may need to open the URL in a new tab, turn on developer mode, and then press refresh to get the proper data.

http://data.pr4e.org/intro-short.txt

Note: If you look at the headers and not all of the headers are present, it may be that your browser is caching the request. Look for the HTTP Response Code in the developer console. Normally you should see a "200" code indicating a normal document retrieval. If you see a "304" status code, it means that your browser is likely using a cached copy of the file.

To convince your browser to actually retrieve the document, clear your browser cache and re-retrieve the document, or add a key-value pair to the URL like:

http://data.pr4e.org/intro-short.txt?x=12345

And then retrieve that URL. To force a fresh retrieval, simply change the value for x= to any new value and re-retrieve the page until you get a 200 status code.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/xyMxrahNEees8xJDNprx2g_0d435d7e06b1494928b08243bcaf3759_http_headers-01.png?expiry=1643155200000&hmac=KC8GgQyOntJrlxD1PVOmqGzynVOQ_rEKxK11bI2jbjA)

Click on Autograder: Request-Response Cycle to submit your assignment.
