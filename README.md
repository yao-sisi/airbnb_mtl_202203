# Airbnb Montreal - Revenue Analysis with SQL and Tableau

As someone who is interested in becoming a data analyst/data scientist in tech/media, Airbnb is one of the companies I follow closely.

There are a lot of datasets on Airbnb out there and I didn’t know why until a week and a half ago when I stumbled upon a website called Inside Airbnb. Naturally, I thought it was a good idea to take a look at the data on my home city of Montreal and see what I can find.

The data contained more than one table and looked a bit messy, I decided to do some light cleaning and EDA in SQL before moving on to visualizing my findings with Tableau.

## Data Exploration and Storytelling


I went into the analysis with one main question — if I was an Airbnb employee, how would I turn the data I have into actionable items in order for the company to optimize its revenue.

First and foremost, I needed to define the KPI(s) to use to measure revenue as I didn’t have access to Airbnb’s actual revenue information.

I decided to estimate the revenue potential by the total earnings of all active listings in the next month(30 days).

Namely, Revenue Potential = Price x (30 — availability_30).

I then needed to define what “active listings” mean in this analysis — it would mean that the listing’s last review was made no earlier than October 2021.

With that in mind, I dove into the analysis looking for the main revenue contributors (by different variables), and whether Airbnb has exhausted their revenue potential.

Here’s the [SQL code](https://github.com/yao-sisi/airbnb_mtl_202203/blob/main/SQL) with my thought process as comments.

Here’s the [Tableau Viz](https://public.tableau.com/views/AirbnbMontreal/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) presenting my findings and recommendations (interactive).

<img align="left" width="700" height="350" src="https://miro.medium.com/max/700/1*qQ7ogvbh-vUXT_9gDup0lQ.png">
