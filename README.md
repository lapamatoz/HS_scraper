# HS_scraper
These piece of code is used to fetch contents for a Helsingin Sanomat (HS) -paper for a particular date. The result is a well-organized json, including paper sections, article titles, urls and IDs.

Feel free to use the code however you want.

## How does it work
First, we find the ID for the paper. The ID is then used with a hidden API that fetches the contents.

## About the paper ID
The paper ID is *almost* always systematically incremented daily. However, a correct ID can be found at the regular website of the paper. This method is used in the code.
