# Random Quote Machine with Jquery

## Features:
   1. Get a random quote by clicking the "Get new quote" button
   2. Share a quote of your liking to twitter by click the "Share to twitter" button

## Descriptions:

This was done by using a rest API created by lukePeavey
https://github.com/lukePeavey/quotable#get-random-quote

Here is the end point that was used to get the data from https://api.quotable.io/random. It will give you a random quote in the database everytime you call it. Since we only need a random quote everytime a user clicks the button and load a random when web site is first load.

Using jQuery to connect to the API, getting the infos, then extract them, eventually display them on the web page. At first you have to refresh the page to get a new quote. Then I implemented a button so that whenever you click it, it will give out a new quote and the name of the author.
