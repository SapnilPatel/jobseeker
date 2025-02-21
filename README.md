# JobSeeker Project

## Overview
1. Recruiter AIs scan your résumé for keywords. If they don’t find the keywords, they discard your application. Let’s increase your chances at landing the job :)
2. When you do get invited for an interview, you are bound to bump into the question "What is your expected salary?" Most of us have no idea what to answer. Let's give you a leg up!

## Our customer
We do this project for the mythical Job Seeker

## Our job types
- Data Engineer
- AI Application Developer
- AI Strategy Consultant

## Features
- Scraping job postings
  - use something like [apify.com](https://apify.com/bebity/linkedin-jobs-scraper?cmdf=linkedin+job-search-api)
  - do the scraping ourselves
- Identifying skills gaps in resumes
- Providing salary range information

## Data Ingestion/Curation - [Medallion Architecture reference](https://www.databricks.com/glossary/medallion-architecture)
- Bronze Folder = Raw data sets labeled by sources. i.e. Data ingested using Apify from linkedin is stored at - bronze/apify/linkedin
- Silver Folder = Cleansed and conformed data. i.e. Data ingested using Apify from linkedin is transformed to contain the information we want to utilize to potentially assist job seekers, such as Job description, title, location, etc...
- Gold Folder = Curated solution ready data. i.e. Data cleaned and conformed that is ready to be used for providing insights to job seekers on improving their resume or skills to be more desirable in the job market.

## Contribution
Your contributions are welcome! Here's how you can help:

- **Suggest Ideas**: Open an 'issue' on our GitHub page and mention it's a suggestion.
- **Report Bugs**: Found a problem? Share it the same way and describe what you found.
- **Make Changes**: Want to fix or add something? 
  - Fork our project (this makes a copy).
  - Make your changes in your copy.
  - Send a 'pull request' so we can review and add your changes to the project.
  
Don't worry if you're new to this – we appreciate your help and are happy to guide you along the way!

