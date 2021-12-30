# Goal
To compare which states have attracted the most H1B visa holders over the past decade and how the employees' average salaries compare
Data source: [My Visa Jobs](https://www.myvisajobs.com/Reports/)

#### Tech stack
1. Jupyter Notebook
2. Selenium

##### Errors encountered
**Error:** Element not interactable
**Solution:** From initial searches, I was prompted to use a wait time but that didn't work (unless of course I didn't apply sleep time correctly). So I changed my approach and looked up a different way of selecting links inside list (li) tags, and found [this](https://stackoverflow.com/questions/44603217/selenium-find-link-within-li-tag-and-click) which worked!