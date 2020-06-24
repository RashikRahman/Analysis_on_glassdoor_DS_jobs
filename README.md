# Analysis_on_glassdoor_DS_jobs

## Code and Resources Used
Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium <br>
Scraper Github: https://github.com/arapfaik/scraping-glassdoor-selenium<br>
Scraper Article: https://towardsdatascience.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905<br>


## Web Scraping<br>
Tweaked the web scraper github repo (above) to scrape 1000 job postings from glassdoor.com. With each job, we got the following:<br>

Job title<br>
Salary Estimate<br>
Job Description<br>
Rating<br>
Company<br>
Location<br>
Company Headquarters<br>
Company Size<br>
Company Founded Date<br>
Type of Ownership<br>
Industry<br>
Sector<br>
Revenue<br>
Competitors<br>

## Data Cleaning<br>
After scraping the data, I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:<br>

Parsed numeric data out of salary<br>
Parsed rating out of company text<br>
Made a new column for company state<br>
Added a column for if the job was at the company’s headquarters<br>
Transformed founded date into age of company<br>

### Made columns for if different skills were listed in the job description:<br>
Python<br>
Excel<br>
AWS<br>
Spark<br>
Column for simplified job title and Seniority<br>
Column for description length<br>
Column for avarage salary<br>

## EDA
<a href="https://imgur.com/Oaqh0Yq"><img src="https://i.imgur.com/Oaqh0Yq.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/YPqdmKP"><img src="https://i.imgur.com/YPqdmKP.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/efq9xD6"><img src="https://i.imgur.com/efq9xD6.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/KnfEYsC"><img src="https://i.imgur.com/KnfEYsC.png" title="source: imgur.com" /></a>
