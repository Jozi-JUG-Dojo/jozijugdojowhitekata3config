jozijugdojowhitekata3config
===========================

This project goes with the kata at http://www.jozijugdojo.co.za/kataw3

NB. This is a project that should NEVER be committed to GitHub because it contains your private keys!

Go to https://apps.twitter.com/app/ and generate the keys as instructed in the kata.
Edit the twitter4j.properties file and enter the four values you received as follows.

#debug=true
#All four oauth tokens are required
oauth.consumerKey=[Put your API key]
oauth.consumerSecret=[Put your API secret]
oauth.accessToken=[Put your access token]
oauth.accessTokenSecret=[Put your Access token secret]
#If you are behind a proxy enter the below
http.proxyHost=
http.proxyPort=
http.proxyUser=
http.proxyPassword=


