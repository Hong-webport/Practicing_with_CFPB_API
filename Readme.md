## Process So far.


# Plan as of 072523

Shrink the data down, use more data from Ipsum, with different valuables, then merge and use sklearns model to predict if it happen in 2023

# Data Sources:

The Consumer Finanacial Protection Bureau (CFPB) had a great site. Easily navigatble. Can easily pull JSON, CSV, and filter what I need.

The US Census Bureau is one of the worst I've ever had to encounter. I need a simple State, and Piopulation, but there are so many unrelated reports. I can say that the worst part of the process so far is navigating through it. I decided to abandon it, and choose WorldPopulationReview.com which is what Wikipedia chose as its reference.

There are other people who can said searching that site took them many hours just for very simple datas.

# Step 1

Pull data to examine it. 

I try to avoid massive data cleaning. To do that, I refocus on variables that can be more manageble. I decided to focus on whether the companies respond is "TIMELY". That give me a set of 6000+ data to work with rather than over 200k.

Most of what doing so far is examining data using the visulation tools like Folium and Seaborn. I make about ten maps/charts to see what should I am looking for. 

After checking several factors I decided to use states as it gave me 51 points to look at.

# Step 2

There are less information for states from CFPB so I decided to got US Census, but that site is waste of time in navigating through it. I decided to go to where Wikipedia pull their data from and merge those data together with what I have. 

The more I do it, the more I see either more data needed or more data mapping.

