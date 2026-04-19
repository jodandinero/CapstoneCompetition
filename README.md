# CapstoneCompetition

## Summary of Business Problem and Project Objective
MasterControl has introduced a new product line, the MX line, which is underperforming in sales conversions. Specifically, MX leads convert at a 12.7% rate compared to QX leads, which is their legacy solution with a conversion rate of 19%. We have been asked to identify an ideal customer profile to focus conversion efforts and to identify key job titles to create a targeted outreach program.

## Our Solution to the Problem
We decided to take a twofold approach. First, we rank the leads through traditional supervised model work (logistic regression, random forest, XGBoost). We then look into the top 20% of the leads by score, which have a very high conversion rate. This helps us get an understanding of the type of customer that converts well based on things like industry, size, manufacturing model, etc. Once we have identified which companies make up our ideal customer profile, we want to find out who within those companies to reach out to. We do this by performing topic modeling on the free-text "Job Title" field. We then compare the topics created to the target and identify relationships that give us a good idea of which job titles will convert and to whom MasterControl should send marketing materials.

## My Contribution
I did all of the topic modeling work. I also tried my hand at some of the supervised modeling, but the results were subpar and were left out of the final presentation. Of note, some of my topic modeling only made it into the shared modeling notebook "additionalmodeling.rmd" This is where I did the cross-performance analysis between the topics and other features.  

## Business Value of the Solution
Our solution will help MasterControl in many ways. The lead ranking will enable their sales team to focus their efforts only on those leads which are likely to convert, so they can stop wasting time and money on fallow ground. Additionally, through the identification of the ideal customer profile, MasterControl can set their sights on more appropriate companies with their marketing materials. Lastly, the topic modeling will prove very helpful on their search for clients. The output is easily understandable, and the cross-referencing of topic with other features will help them home in on individuals within companies who are most likely to purchase their product. They can use these job titles as search terms on LinkedIn and feed new job titles into the model to see if they are a good candidate. 

## Difficulties
At times it was difficult for our team to stay focused on an overall vision for the project. Members had ideas about what they wanted the full analysis to look like and were not receptive to feedback. There were numerous 3 hour meetings where we were discussing our approach and what would be best for the project. We did eventually find a way to work together to turn out a good product. 

## Takeaways
The biggest thing I learned thorugh my work and the feedback throughout the course was the importance of conveying the value of the work. I was thoroughly convinced of the topic modeling value, but it took me numerous rounds of feedback to be able to convey the value in the presentation. This was also honestly a big learning experience in how to work with a strong personality on the team. The way that we needed to manage that was not easy to find and took a lot of learning on my end. 
