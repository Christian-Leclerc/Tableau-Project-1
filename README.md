# Tableau_Project-1

## Purpose and Goals

This repository contains an analysis of the Wildlife Strike from the Federal Aviation Administration database (FAA) of the United States from 2000 to 2015.
![FAA Logo](/images/FAA%20Logo.png)
[www.wildlife.faa.gov](https://wildlife.faa.gov/home)

The intent was to use my new skills using [Tableau](https://www.tableau.com/trial/tableau-software#reveal-hero) to conduct exploratory visuals analysis, create a dashboard and present a story answering a specific question. The focus of the analysis was to ***help airports and airliners pin point the scope of the problem*** for their specific location and help them identify the risks and the **cost** associated to it.

## Process
<div>
    <p align="center">
        <img src="/images/Process.png" align="left" width=300px style="margin-right: 20px">
        <div>
            <p>In the data folder, you will find the cleaning_data.ipynb Jupyter Notebook that explain my process of cleaning and preparing the Excel file extracted from the FAA (given by the LightHouse Labs school).
            </p>
            <p>With the cleaned file, I used Tableau to create several visuals while exploring the data trying to find relevant trends, outliers and any interesting insights.
            </p>
            <p>I eventually identified a question I wanted to answer and created a Dashboard to help answering it and presenting it to the school students.
            </p>
        </div>
    </p>
</div>

<br>

## Results
There was two options to choose from the school scope of work. The standard option where the questions were already pre-determined and the other option where we determine our own question and the way we want to create the dashboard. 
I chose the FAA Wildlife Strike from the second option list. It came with an Excel sheet with the data extracted from the FAA from 2000 to 2015 of all the reported wildlife strikes at each airport of the United States.

From the FAA website, a lot of insights are already known that explain the **increase in the number of reported strikes** such as:
<div>
    <p align="center">
        <img src="/images/Sully.png" align="right" width=300px>
        <p>
            <ul>
            <br>
                <li>Expanding wildlife populations</li>
                <li>Increases in number of aircraft movements</li>
                <li>Trend toward faster and quieter aircraft</li>
                <li>Outreach to the aviation community</li>
            </ul>
        </p>
        <br>
    </p>
</div>

But, in my opinion, what airports and airliners wants to know to be able to do something is the **cost**. How much should I invest, why and where?
So all my visuals were "paired" with some kind of information with the cost, especially the cost of damage and the total out of service hours.

I divided my scope of work in 4 steps:
- **TRENDS**

- **WHEN** the damage occurs

- **EFFECT** of the damage

- **WILDLIFE** associated to the damage

My objective, or question, is how can I build a Dashboard to showcase the cost of the damage and help the airports manager to quickly identify WHEN it most occurs, whats the EFFECT on the fleet and what type of WILDLIFE is most problematic to be able to define a mitigation plan. 

DASHBOARD
![TREND](/images/Dashboard_trend.png)

In the upper part of the dashboard, the manager can select which State and Airport is in to update the numbers automatically.
At the bottom left, the maanger can decide which year to focus on.

I already defined 4 metrics:
- Number of strikes
- Pourcentage of these strikes that have damage
- Total hours out of service
- Total cost of damage

Below the metrics, the manager can switch between the 4 different categories of graphics that I have selected with the most insights.

![WHEN](/images/Dashboard_when.png)

At any time, the map on the upper right corner can be switch between Strikes and Cost to see the distribution around the united states.

![EFFECT](/images/Dashboard_effect.png)

Of course, its a Tableau Dashboard, so any choice make as filters will update any of the graphics in any categories... all in one place.
![WILDLIFE](/images/Dashboard_wildlife.png)

I have also imbedded a link to a web page call [ebirds.org](https://science.ebird.org) so they can easily find an image of the bird associated with its name (more visual). Also, this site provides a lot of information on abundance, migration path, etc.

What did I discover?

-  Number of strikes greatly depends on human activity, specially during holidays.

-  Most of the strikes happen during Day and Night, 2X more during day.

-  Number of strikes increase but not that much for cost of damage (except for rare destroyed aircraft).

-  Most of the damage are substantial, so the out of service hours are very high.

-  Most of the strike happen during climbing.

-  Canada goose are having the most impact on cost.

-  Most of ducks are beeing strike at night.



## Challenges 

It was my first time with Tableau. It was a bit frustrating to know exactly what I want to have as a visual, but not knowing how nor even if Tableau can do it. Also, born with PowerPoint, I found text formating very tiedious in Tableau and extremely limited. Make sense since the idea is to show visuals, not text... 

## Future Goals

If I had more time, I would have try "pairing" airports. Meaning, to be able to compare two airports and say they are similar to the wildlife environnement, species, strike levels, etc. Then comparing there different damage cost and see how they can help each other adopt rules and ideas to mitigate the risks.
