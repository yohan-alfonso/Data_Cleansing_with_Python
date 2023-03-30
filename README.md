# Data_Cleansing_with_Python

This repository is about Data Cleansing since it's maybe the most importan part of a project.
Most people belive that clean data is just erase strange characters in data but it goues beyond that assumption
Datasets migth be dirty in strcuture, content dirty or both.

Lets see some cases tha opens your mind about the types of dirty and how to solve each situation



# About Dataset

### Context

This is a pre-crawled dataset, taken as subset of a bigger [dataset (more than 4.7 million job listings)](https://datastock.shop/?utm_source=mn-kaggle&utm_medium=referral) that was created by extracting data from Monster.com, a leading job board.

### Content

This dataset has following fields:

* `country`
* `country_code`
* `date_added`
* `has_expired` - Always `false`.
* `job_description` - The primary field for this dataset, containing the bulk of the information on what the job is about.
* `job_title`
* `job_type` - The type of tasks and skills involved in the job. For example, "management".
* `location`
* `organization`
* `page_url`
* `salary`
* `sector` - The industry sector the job is in. For example, "Medical services".

### Acknowledgements

This dataset was created by PromptCloud's in-house web-crawling service.

### Inspiration

* What kinds of jobs titles correspond with what kinds of wages?
* What can you learn about the Moster.com-based US job market based on analyzing the contents of the job descriptions?
* How do job descriptions different between different industry sectors?
