# csuf
COVID19 data sentiment analysis UPDATES

PracticeCSUF.Rmd: ***this uses SAOTD***
*main website I've been liking: https://rdrr.io/cran/saotd/f/vignettes/saotd.Rmd and got it all to work with their practice dataset, just not with mine...
* something is wrong with the 'key' part of twitter developer tools (especially with tweet_acquire)
    I am having trouble mostly with the filename/file.path(tempdir() part because I can't find any examples of this without using this airline sentiment practice data
    I think this key part will help with the problems I'm having at toward the bottom of this document when trying to get sentiment scores and topic analysis (that won't run because they say something is wrong with the key)
    I think if this part is worked out, maybe would be more doable to work on the topic analysis/visualization part at the end of doc
    
    
CSUF.Rmd: ***this uses primarily rtweet
* problems with this: only takes from last 6-9 days
* thought about using geolocation to just look at where tweets were coming from, but turns out only 1% of tweets are geocoded and even though I made a google API to get the geo coord data, I couldn't get it to work and when I subsetted it to look at long and lat, only NA values appeared
* I WAS able to get some kind of sentiment analysis going here though, but kind of similar to SAOTD from doc above^^
* not sure which is better, but this is as far as I have been able to get...

Overall questions:
* what do you think I should be looking for in this sentiment analysis broadly (like specific words, trends, etc.)
* I think i need help authenticating the key and stuff with the SAOTD file
* should I try and use geolocation or how should I go about starting that?
* overall, what next steps do you think I should be focusing on... I'm kind of lost now:/
