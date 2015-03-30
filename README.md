# interesting-data-sets
This is a stub. The core of this repository will likely be a JSON file of urls for interesting public data sets, of interest to those who follow the news in the Mid-Atlantic region. We will probably create some sorts of alerts based on these, with the idea of hooking projects atop them when they change.

TODOS (mostly OYOT): 
- Create the spreadsheet listed on the *last* step of this to-do list. It's actually the important part. The rest is all just a fun way of ultimately opening up our already-used data by default.
- Create an initial JSON file -- make it flexible!
- Import existing urls from your current alerts on changealerts.com
- Since it's *usually* likely that a given data set is either outside the scope of our default scraper and/or better served by other tools, add links in the readme to external tools like Google Alerts, FOIAMachine, pandaproject.net, ScraperWiki, Kimono, Import.io, MuckRock, etc.,.
- If it's not present already, you should include a field in your JSON file that signifies which kind of tools we might be able to use. Maybe also include a field signifying the tool we ultimately choose to use -- possibly along with a link to a specific scraper or project page.
- If it's not present already, add another field to each source on your JSON file listing story ideas related to a given source. Include a "see private doc" option that points to something only the team can see. (This can be used frequently -- by default, even -- and allows us to be relatively transparent while not giving away everything we're working on.)
- Create a simple way for the team to contribute their own sources. Test it, then show it to them. (Maybe this is a google spreadsheet that we selectively pull from via a server script? Not sure.)
