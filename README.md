# Insurance-Analytics-PowerBI
                                                               Introduction
In this project, we use the Power Bi visualization tool to create an interactive dashboard for insurance policy data.
Insurance data analytics refers to the process of collecting, analyzing, and processing insurance-related data to extract valuable insights from it to manage risks and calculate the optimal insurance contracts for firms. 
In essence, it's a combination of data analytics and the insurance industry that helps insurance companies leverage the power of data and employ big data techniques to quickly study the available data and convert it into valuable insight. 
Data analytics defies how traditional insurance is done and provides a vast deal of growth opportunities previously never uncovered.

An insurance claim is a formal request made by the policyholder to the insurer for compensation against losses covered in the insurance plan.
It provides financial assistance to the policyholder during unfortunate circumstances.
Moreover, the insurance claim adjuster helps discover a reasonable settlement offer.
while, a non-claim in simpler terms is, if a policyholder does not make any claim within a policy year, the Insurer awards them with a benefit known as NCB or 'No Claim Bonus'. 
Offering this benefit is a way through which Insurers encourage their consumers to stay healthy and file a claim only when it is necessary. 

There are three different types of policies listed in this project, one of them being premium which means the Insurance premium is the cost of your insurance policy. 
It is the amount that you pay to your insurer in exchange for which you get the policy coverage. 
The second one is platinum, one of four healthcare coverage categories, or "metal levels," you can purchase through the individual marketplace. 
Although platinum plan health insurance often has the most expensive monthly premiums out of the four metal levels, these plans provide guaranteed coverage for specific services and have the lowest co-pays and deductibles. 
The last one is basic which can be seen as the purest form of a life policy, and that is a traditional term life insurance policy.  
What makes it a basic policy is that it is simple in the fact that you pay for a specific amount of coverage for a certain amount of time. 
These policies will also have a guaranteed level premium, and your coverage amounts will not decrease due to your health.



                                                              Methodology
1. Start
2. Integrating data source with power query
3. Querying data onto the navigator
4. Editing the queries on the table
5. Shaping the data according to requirements
6. Merging queries from different tables
7. Creating visuals (charts, graphs, maps, etc) using different metrics in the table
8. Loading the Report onto the Power BI Desktop



                                                 Creating measures using DAX (Data Analysis Expressions)
1.	non smokers = CALCULATE([total insurance policy],POLICY[smoker]=0)

2.	smokers = CALCULATE([total insurance policy],POLICY[smoker]=1)

3.	TOTAL CHARGES = SUM(POLICY[charges])

4.	TOTAL INSURANCE CLAIM POLICY = CALCULATE([total insurance policy],POLICY[insuranceclaim]=1)

5.	total insurance policy = COUNT(POLICY[insurance policy_id])

6.	TOTAL NON INSURANCE CLAIM POLICY = CALCULATE([total insurance policy],POLICY[insuranceclaim]=0)


                                                              Maintainer

This project is actively maintained by Pooja Patel.

Pooja is a Data Science Graduate with expertise in data visualization, statistical analysis, and dashboard development using tools like Power BI. She focuses on transforming complex data into clear, actionable insights.

For inquiries or collaborations, please reach out:
- Email: patel.pooja81599@gmail.com
- GitHub: [Your GitHub Profile]
- LinkedIn: [Your LinkedIn Profile]