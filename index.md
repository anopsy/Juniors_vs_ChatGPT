### TODO:
#### 1: Replace donuts charts with bar charts
#### 2: Change the charts showing increase/decrease from horizontal to vertical.
#### 3: Create a plot showing mean compensation change per country
 

## Has ChatGPT replaced Juniors and Interns?
In order to answer that question I’ll have a look at two datasets I obtained by querying the API of SourceStack - a company that aggregates job offers.
You can have a closer look at the data in the datasets_analysis.md

I’ll formulate my question into a more concrete questions, I’ll try to find an answer to:

#### 1. Did the number of  Junior and Intern roles drop significantly in 2024 as compared to 2023?

In June 2023 Junior job offers were 1.674% of the total 50000
Internship offers were 1.504% of the total 50000

In April 2024 Junior job offers were 2.118% of the total 50000
Internship offers were 2.46% of the total 50000

Entry-level jobs (Junior + Intern) in June 2023 were 3.178%
Entry-level jobs (Junior + Intern) in April 2024 were 4.578%
but if we look closer, we can see a significant increase in the number of entry level jobs.
The number of entry-level jobs has risen by 44% 

![image](https://github.com/anopsy/junior/assets/74981211/306c7e9e-07ca-4058-a1ff-6f10fc7f34fc)

#### 2. Did the share of Junior and Intern roles within the group of IC jobs shrink in 2024 in comparison to 2023?
Let's first have a look at the number of jobs by type.
In the datasets we could discern two types of jobs: 
leading jobs including:
Director, Chief, Exec, Manager, Senior Manager and Founder,
and
IC jobs including:
Intern, Contract, Junior IC, IC, Senior IC and Staff IC.

The share of each job type remained constant.

![image](https://github.com/anopsy/junior/assets/74981211/f9541adf-89eb-4f38-b515-c487dffaf3fb)

But if we compare the share of IC roles, we can see a confirmation that indeed the share of Junior and Intern roles increased.
Junior roles share went from 5.29% in 2023 to 6.53% in 2023.
Intern roles grew even more from 4.08% to 7.21%.
Which seniorities appeared less often in the job offers postings: Senior IC jobs and Contract jobs by respectively 2% and 1%.


![image](https://github.com/anopsy/junior/assets/74981211/8f603762-3458-4816-9a17-b9bf946fde02)


We could also compare the number of jobs published every day in the last 90 days from the sampling date.
A clear increase in the number of job postings is visible in the case of Intern roles.
Which corresponds with the 3% increase in the share of IC jobs.
The trend for Junior roles is not that clear and obvious.
![image](https://github.com/anopsy/junior/assets/74981211/fee85f1c-0437-4009-919b-fe072069e328)

We can also look at the mean weekly values for the number of job offers being published.
Again we see a clear increase in the number of Intern jobs and not a clear increase in the number of Junior roles.

![image](https://github.com/anopsy/junior/assets/74981211/87a816d6-a8bc-48c0-8261-59aa0b8c73ed)


![image](https://github.com/anopsy/junior/assets/74981211/20e7f995-a881-42e8-a8b9-9c8487dc7d7c)



####  3. Did the yearly mean compensation for Junior or Intern roles change in 2024 as compared to 2023?
Yes it did for Junior Roles. The mean compensation estimation for Junior IC job offers dropped by almost 10K dollars.
While the mean compensation estimation for Intern roles remained roughly the same.
  
![image](https://github.com/anopsy/junior/assets/74981211/ffc32c71-8341-4a06-a2ac-d759ce4c6f24)

Let's plot the differences year to year, we can see that the Junior IC and IC compensations shrunk the most.
While Interns' yearly mean compensations grew unsignificantly.
What's worth noting is that the lead roles booked a significant increase. 

![image](https://github.com/anopsy/junior/assets/74981211/17e3e7a5-248c-46f0-9730-a0ac32f6d722)

The question that arises are Senior and lead roles responsible for the drop in the mean compensation for Juniors?
Or are there other factors?
The compensation in Engineering vary not only per Seniority or specific job type
but mostly by country and the number of hours. So let's investigate those two variables.


#### 4. Did the number of Junior and Intern roles change per country when we compare 2023 and 2024?
   
The number of Junior jobs dropped slightly for the US and changed drastically for other countries.
In 2023 countries with the most Junior jobs were: US, Germany, UK, Canada and Brazil.
While in 2024 the most Junior jobs could be found in the US, India, Germany, South Africa and Italy.
![image](https://github.com/anopsy/junior/assets/74981211/26c4790d-32a3-4ae6-b905-11f1103b2de7)
![image](https://github.com/anopsy/junior/assets/74981211/4924b028-470f-4242-a477-6c5b46544821)

Let's have a look at the differences in Junior jobs offers per country.
We can see that the number of jobs dropped most significantly in the US, and increased a lot in India.
Which could be a main reason for the changes in the mean compensation between 2023 and 2024.
(Let's assume for now that the mean compensations in US are higher that in India, and I'll add a plot for this later)
The number of Junior jobs dropped in 2024 also in Germany, Canada, Brazil, UK, Netherlands, Mexico, Spain,Portugal and Israel.
It increased the most in India and South Africa, but also Indonesia, Poland, Argentina, France, Italy, Greece and Romania.
![image](https://github.com/anopsy/junior/assets/74981211/47dff527-4ad5-4dbb-b22e-10c02260e1c8)


Let's have a look at the number of Jobs for Interns.
Here we see a huge increase in the number of open Intern positions in the US.
It's an increase of more than 300 job openings. Another countries that can offer now more work for Interns are:
India, UK, Germany, Singapore, Brazil, France, Taiwan, China and Italy.
The number of Intern job positions dropped most significantly in Canada and Vietnam.
Again assuming that US Interns are better paid than European, South American and Asian Interns, we might have found the culprit, 
explaining the rise in the number of Junior and Intern roles but a drop in the mean compensation for Juniors and increase in the case of Interns.
![image](https://github.com/anopsy/junior/assets/74981211/9d1183ba-2e17-4974-af28-598b50f55ede)
![image](https://github.com/anopsy/junior/assets/74981211/210df084-17aa-432f-98c0-aa2f2098178b)
![image](https://github.com/anopsy/junior/assets/74981211/91360d74-b5ce-4097-88e6-9b65f0892b9e)


Out of curiosity I also wanted to compare the changes in the number of remote job openings and also most popular job names and companies.   
# 5. TODO How compansation changed per country?
##### 5. Remote Jobs changes
Interestingly both the number of remote and non-remote jobs dropped and the number of jobs with an unclear status for possibility of working remotely increased.

   ![image](https://github.com/anopsy/junior/assets/74981211/e381952c-72cb-46c5-b1cd-8c7b207a81f5)
   ![image](https://github.com/anopsy/junior/assets/74981211/4d7be6f0-e1bb-416a-bbdf-f2a16942aa04)


##### 6. Most popular Junior Job Names.
In 2024 the absolute leader in the number of job openings is Fron End Entry Level. While in the 2023 there were a lot of demand 
for Junior Data Scientist specifically in Dubai. It could also be a company that posted the same vacancy on different occasions.
    Junior Jobs
    ![image](https://github.com/anopsy/junior/assets/74981211/e48d207d-18b3-4888-a28b-4b0846bc621f)
    
Interns would have the most changes to land a job if they were looking for a vague "Engineering Intern" position both in 2023 and 2024.
For 2024 we can also see a lot of non-It engineering Intern position e.g Civil, Electrical and Mechanical Engineering
While in 2023 the most common positions placed just after the Engineering Intern were Software and Biomedical Engineering Interns.
    Intern Jobs
    ![image](https://github.com/anopsy/junior/assets/74981211/47a21fa1-6496-471a-b101-b625e6b952f7)

##### 7. Companies.
Juniors were in demand in Dubai (but as mentioned earlier it could be due a company posting multiple job posting at different occasions)
IBM and Proautomated were also offering job opportunities to Juniors. In 2024 Albertson Companies and Rosebank College were the leaders among Juniors' employers.
But the number of unspecified companies has risen in 2024.
![image](https://github.com/anopsy/junior/assets/74981211/7f299b4f-fb09-48fa-b4ac-bcbb5e02632c)
    
Intern Jobs were offered in 2023 mostly by companies such as Volvo, Bosch, IMB and AMD.
The next year only IBM kept the high number of Intern positions and the number of unspecified companies rose in 2024.
![image](https://github.com/anopsy/junior/assets/74981211/893aaaf0-a8fb-4d2d-9de0-6a4331b50c42)

### Conclusions:
The analysis of junior and intern job opportunities across various countries from 2023 to 2024 reveals significant shifts in the job market. The overall number of entry-level jobs increased, indicating a growing demand for junior and intern positions globally. While the number of junior jobs in the US experienced a slight decline, other countries saw more drastic changes. In 2023, the countries with the most junior jobs were the US, Germany, the UK, Canada, and Brazil. By 2024, the landscape had shifted, with the US, India, Germany, and South Africa leading in junior job opportunities.

The most notable changes include a significant increase in entry-level opportunities in India, propelling it to second place, surpassing Germany. Conversely, the US saw the largest decrease in junior jobs, while India experienced the most substantial growth. The number of intern positions increased the most in the US, with a notable drop in Canada.

These changes in job distribution and availability may have influenced the mean compensation for junior and intern roles, with the US generally offering higher pay compared to other regions. The increase in junior and intern roles in the US and India, coupled with changes in compensation, highlights the dynamic nature of the global job market.

In relation to the null hypothesis that “ChatGPT replaced juniors and interns,” the data suggests otherwise. The increase in entry-level job opportunities indicates that the demand for human talent in junior and intern roles remains strong, despite advancements in AI technologies like ChatGPT.





