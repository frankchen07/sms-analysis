Frank Chen (fc2451@cumc.columbia.edu)  
Ryan Quan (rcq2102@cumc.columbia.edu)  
Florence Lee (fcl2114@cumc.columbia.edu)  
TramAhn Lai (tl2580@cumc.columbia.edu)  


# Background

Mental health is an often understated topic within the wellness community and has the potential to be highly stigmatized. The negative impact of mental illness on individual wellbeing carries a price tag of almost 300 billion dollars per year, impacting our healthcare system by an overuse of disability support payments and losses in potential earnings. 

Inadequate services and stigmatization of mental illness have dissuaded many from seeking proper treatment. Approximately 40% of individuals in the United States are currently untreated and are not receiving adequate treatment. This furthers the cost burden upon the healthcare system, as individuals living with depression, one of the most common mental illnesses, are more prone to hypertension, cardiovascular disease, stroke, and obesity. Furthermore, such individuals are less likely to participate in prevention programs, and many rack up support payments and indirect costs associated with chronic disabilities. This stigmatization leads to discrimination, which further prohibits individuals from seeking proper help.

If one narrows the focus upon college and university campuses, the statistics are glaring:

1. 75% of lifetime cases of mental health conditions begin by age 24.
2. One in four young adults between the ages of 18 and 24 have a diagnosable mental illness.
3. More than 25% of college students have been diagnosed or treated by a professional for a mental health condition within the past year.
4. More than 11% of college students have been diagnosed or treated for anxiety in the past year and more than 10% reported being diagnosed or treated for depression.
5. More than 40% of college students have felt more than an average amount of stress within the past 12 months.
6. More than 80% of college students felt overwhelmed by all they had to do in the past year and 45% have felt things were hopeless.
7. Almost 73% of students living with a mental health condition experienced a mental health crisis on campus; 34.2% reported that their college did not know about their crisis.

Most contemporary universities boast a sizable student population, most of which own and use smartphones. Hundreds of smartphone applications have been published in the past decade, allowing both individuals and clinicians to track mental health status over time and more recently, deliver therapeutic interventions. Many applications (MoodBug, Optimism, Priori, Miobilyze!, StudentLife, and Mind's Eye) have progressed quickly, often used in conjunction with wearable devices (JawBone and FitBit) that can detect physiological changes, and roughly detect emotions and moods through frequency of conversation, activity levels, changes in speech patterns, and memory tracking.

Many of these applications are automatic in nature, running in the background and providing feedback to the user, but fail to account for the individual baseline differences. Often times, applications fail due to lack of motivation or accuracy scores. 

# Problem Statement

(motivating users to track their data)
(exploring new types of data to track that pertain to health)
(providing users with feedback on their data)
(enabling sharing of data with other individuals and with the research community)

SentiMENTAL offers a unique perspective on personal relationship analysis, providing personal insight and sentiment analytics that contribute to a growing repository of de-identified SMS data. The repository of training data would eventually be utilized by researchers in a potential classification task for identification of mental health disorders. The draw of submitting SMS data comes from access to individual relationship analytics (response rate to/from friends, topics most discussed, average mood during the day), thus, layout of the application will come in tiers, involving the user to label their own training instances (is this text happy? sad? angry? etc). The more participatory a user decides to be, the more access to relationship analysis and sentiment analysis conclusions will be offered. For researchers, this eventually will result in a rich body of labeled text for classification tasks. 

# Working Code URL

[Link](https://github.com/frankchen07/sms-analysis/blob/master/sms_analysis_raw.Rmd)

# Tiers of Engagement

1. Top-Level (Researchers)
    * continuous data collection
    * large repository of sms sentiments
2. Middle (Data Enthusiasts)
    * front end developers (app-user interfaces)
    * back end developers (how to store the data)
    * data scientists (new metrics and analyses)
3. Bottom (Average User)
    * word cloud of major events (e.g. 9/11)

# Thoughts

* How do you get someone to give up SMS data?
* How to pique curiosity (relationship summaries and visualizations) while preserving confidentiality?
* How do we ensure data submission (training set) validity?
* What would you want to share with your social network?
    * getting better at responding
    * general sentiment score
    * comparison metrics
* How does one "compete" within this community?

# Requirements and Evaluation Criteria
Opt-in and transparent policy regarding providing access to one’s own data
Mechanism for sharing data with Columbia health data science researchers
Flexibility and extensibility regarding the types of data and collection devices

# Potential Barriers:
What should people have access to?

# Final Product:
One-Button Reporting Feature

# References