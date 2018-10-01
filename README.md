fake-jersey-ml
==============

An experiement to identify fake ice hockey jerseys. For Europeans it's shocking to find out that there are so many fake hockey jerseys and then even more shocking to find out the cost of a fake. This project will try to identify fakes from pictures.

## Data Source

The data source for this project will be r/hockeyjersey's legit check threads. This is where users post a link to photos of a jersey and other users confirm if it's a fake or not.

### How I collected the data

I used PRAW to read all the top level comments in multiple monthly check threads and found ones with ebay or imgur links and then read the second level comments and see if they contained the words "good", "legit", or "real" if they did I marked it as a legit jersey. If they contained the words fake or counterfeit I marked it as not legit. I ignored all other submissions.
