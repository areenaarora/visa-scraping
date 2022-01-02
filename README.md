# Goal
To compare which states have attracted the most H1B visa holders over the past decade and how the employees' average salaries compare. Ideally, I want to write a scalable function that can be replicated across various metrics on this website.
Data source: [My Visa Jobs](https://www.myvisajobs.com/Reports/)

### Process
Identified how to scrape the exact table I wanted to and then wrote a function to perform the scrape for all years (2016-2021) using a list and for loop. Data from before 2016 was not available publicly at the time of doing this scrape.

#### Tech stack
1. Jupyter Notebook
2. Selenium

##### Errors encountered
**Error:** Element not interactable
**Solution:** From initial searches, I was prompted to use a wait time but that didn't work (unless of course I didn't apply sleep time correctly). So I changed my approach and looked up a different way of selecting links inside list (li) tags, and found [this](https://stackoverflow.com/questions/44603217/selenium-find-link-within-li-tag-and-click) which worked!
