# Data-Collecting
Data crawlers and scripts to data collecting used during my PhD. Course

Usually I need to collect data in a data-wars style ;)
This script are a simple courtesy of weapons to this battle.

Actually the project provides the following files:
  - Foursquare Venues Crawler: HTML parser to collect data from venues pages of Foursquare app
  - Twitter Monitor based on Geolocation: simple crawler to collect data from Twitter Stream API
  - Twitter Monitor based on Hashtags: similar to previous, but based on specific keywords of tweets
  - Twitch Viewers: use the API of Twitch to colllect data about a list of streams
  - Twitch Chat: connect to Twitch chat (IRC) and make log of content
  - Instagram Crawler: visit the list of URLs of shared photos on instagram and collects the place/venue indicated on 'check-in'
  - Instagram Crawler Multiprocessing: similar to instagram-crawler, but uses multiprocessing module to make the parallel execution
  - HLTV Crawler: collect data of streams online on hltv.org (viewes, class and country)
  - Foursquare Crawler: collect data from URLs of check-ins on foursquare. Used to determine the context of check-in
  - Foursquare Crawler Multiprocessing: similar to foursquare-crawler, but works in parallel to optime processing time
  - Foursquare Categories: JSON of name of places categories defined by Foursquare
  - Facebook Monitor: monitor of likes and 'people talking' of pages on Facebook
  - OpenSignal Crawler: crawler to collect data of cellphone antenas and quality of signal from OpenSignal project
  - Chicago Traffic Tracker: continously check the JSON provided by CTA dept. about the Chicago Traffic
  - Weather Underground: script to collect historical data about weather in specific locations. The data is provided by Weather Underground repositories.

OBS: all the scripts are python and use some external packages/modules or need a specific input file. 
Feel free to extend your project based on these codes.
