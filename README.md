# US Universities and Colleges KMZ

Just a little project I've been working on in my spare time of placing the logo of every university and college in the United States on a Google Maps in its respective location.

I began by scraping the logos from the user flairs on Reddit sports discussion forums. The icons from the college football subreddit are 60x40 pixels while those from the college basketball subreddit are 70x70 pixels. I made the remaining icons myself and sized them to 70x70 since that was easier to work with.

The flairs I scraped were divided by athletic conference which in retrospect probably was not the best way to approach, but that is how the folders are organized. Part I is all NCAA and NAIA schools. Part II is smaller conferences and a number of non-sports schools. I am sure I am missing many. Part III is community and junior colleges that are associated with an athletic conference. Part IV if I get around to it would be non-sports community and junior colleges.

These can be uploaded onto Google Maps using the My Maps feature. Within each folder in this repository is the folder of icons and a KML file. These should be zipped into a ZIP file which should then be renamed to be a KMZ file. The KMZ can then be uploaded onto a Google My Maps.

The KML file is an XML file and is pretty straight-forward. Google My Maps are limited to ten layers so I could not upload everything onto one map the way I have organized. In order to do that, I had to go into each KML file and remove all the dividing layers so all the schools are in large layer. For example in Part I, there are layers called FBS, FCS, D1 BB, D2, D2 BB, D3, D3 BB, NAIA, and NAIA BB which I removed and placed under one overhead layer titled Part I. Then they can be compressed into a KMZ and uploaded onto My Maps and will appear as one layer.
