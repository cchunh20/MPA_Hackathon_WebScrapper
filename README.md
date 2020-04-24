# Hackathon WebScraper
MPA COVID-19 Hackathon. This webscraper pulls information from large retail sites. Currently Sam's Club and Walmart. The website is accessible here: [CoronaEssentials](http://coronaessentials.info). If domain is not working, connect directly using its [IP](http://23.239.14.146). Website will stay up until May 21st, 2020.


Our solution was to present essential items during this COVID-19 pandemic. We pulled information about essential items from Sam's Club and Walmart using
the dependencies below. We created functions to scrape each individual website for a certain product. These functions used the 'Beautiful Soup' dependency
to get the information from the website and from there, used 'lxml' to parse/analyze that information we pulled. For our website, we utilized 'Flask'
to display the items we pulled from each website. On that website, there's tabs to which bring you to the store, and from there, you can choose to see
what products are currently available. This provides the user to choose what's readily available in a time like this, leading to a more clear way to
get what products they need.

## Dependencies for Local Machines
* [Python](https://www.python.org/) | [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Beautiful Soup 4](https://www.crummy.com/software/BeautifulSoup/)
* [Requests](https://pypi.org/project/requests/)
* [lxml](https://lxml.de/)

## Authors
* [Austin Wong-Parker](https://github.com/AustinWongParker/) (maintainer)
* [Nadya Postolaki](https://github.com/ninjanadya/)
* [Jessica Petersen](https://github.com/jpetersen2/)
* [Chris Chunh](https://github.com/cchunh20/)
* [Mitchell Ford](https://github.com/MitchellTFord/)
