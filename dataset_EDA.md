
   
## Datasets
   The datasets I will use to answer the question come from SourceStack.
   I queried the API on June the 9th 2023 and April the 2nd 2024, getting 50_000 records- sample on each day, resulting in a dataset with 100_000 records.
   The offers are mostly engineering jobs.
   
   ![image](https://github.com/anopsy/sourcestack/assets/74981211/992146c1-85ca-4ffe-bf65-e176a9fcf994)

   
   The dataset has 16 features:

   <br>job_name [str] - job title
   <br>job_location [str] - information about job location 
   <br>hours [str] - information about type of employment full-time/part-time/contract/gig
   <br>remote [bool] - information if the role is remote or not
   <br>company_name [str] - the name of the company
   <br>education [str] - what education is required
   <br>tags_matched/ tag/categories/categories list[str] - tags describing the job
   <br>seniority [str] - information about seniority
   <br>comp_est [str] - estimated compensation offered for this vacancy
   <br>language [str] - language required 
   <br>city [str] - city location of the offered job
   <br>country [str] - country location of the offered job
   <br>job_published_at [str] - the date at which the job was published
   <br>last_indexed [str] - the most current date the job was indexed at

   The dataset contains a significant amount of null values and only one duplicate.
   
   ![image](https://github.com/anopsy/sourcestack/assets/74981211/df8d965a-7d44-4edc-92a0-b342bae0029e)

   The job offers come from 183 countries with 44 languages and 7_795 different cities.

   Countries:

   ![image](https://github.com/anopsy/sourcestack/assets/74981211/3b8ced68-da33-4eb0-8f8d-012ffffa6d54)

   
   ![image](https://github.com/anopsy/sourcestack/assets/74981211/5095f61f-a8fc-478a-97b0-4662ffee480e)

   Top Countries being:

   <br>United States - 44_581 job offers
   <br>India - 10_275
   <br>United Kingdom - 4191
   <br>Germany - 3560
   <br>Canada - 2362
   

   Cities:
   
   ![image](https://github.com/anopsy/sourcestack/assets/74981211/3f5c10e6-8f9a-4ffb-af84-da78f2562827)

  Top Cities being:

  <br>Bengaluru with 1942 job offers in total.
  <br>Bangalore - 1512
  <br>San Francisco - 961
  <br>London - 956
  <br>Singapore - 863


   <br>The job offers come from 28_781 different companies.
   <br>The top 20 companies posted in total 9502 job offers - 9,5% of the total job offers.

   ![image](https://github.com/anopsy/sourcestack/assets/74981211/a7e32a3f-3fde-4466-94ad-b2476ca58068)

   
   Every Job Offers goes alongside with a certain number of tags, ranging from 0 to 150 tags.
   The most popular tags being:

   ![download](https://github.com/anopsy/sourcestack/assets/74981211/10a34450-d94c-4f22-8fcd-241b6f756fab)

   Last but not least are the job names:

   ![download](https://github.com/anopsy/sourcestack/assets/74981211/c3221262-c283-4ad8-be54-b19ad07c77f9)

