# Ravelry
Looking at Ravelry's API, attempting to answer:
- what are the most used brands/weights of yarn?
- the distribution across them?
- the average amount of yarn per project used for them?

Querying the projects, you can click on the thumbnails to see how much and what kind of yarn each project used. 
https://www.ravelry.com/projects/search?query=

Struggles (If it were in SQL tables I'd be comfortable aggregating/analysing it):

 - Accessing ALL projects (seems to max out ~100,000 records).
 - The project json files don't contain "Needs & yarn", which is on the website

API documentation
https://www.ravelry.com/groups/ravelry-api
https://www.ravelry.com/api

