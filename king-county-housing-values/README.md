# Data Collection - From the web.
Used to be done with Beautiful Soup, but now the process is migrating more towards Headless Chrome.

**Note: This API is no longer working.** I wrote this several years ago. I did some updates recently but it looks like the website's data feed has changed. It's in my backlog and I'll get to it eventually

API services and Ipython notebooks to get and analyze data from http://info.kingcounty.gov/
Data is from King County's current web posting.

# Look through housing prices in King County;
You can search through the map here:
http://gismaps.kingcounty.gov/parcelviewer2/
-find your building's parcel number (or a list of them)
-Then this script will extract the historic property value data
-You can pull this also for all of the individual units in a condo
which is what I wanted as I planned on compareing my value to similar units

Eventually I'll have this flushed out into a web app and more robust libary
I just wanted to get it started here. 
