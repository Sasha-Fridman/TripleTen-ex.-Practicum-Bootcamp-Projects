
|Project|Topic|Description|Tools|
|:----------|:--------|:------------------------------------------------------------|:-------------|
|Creating Dashboards to Display YouTube Trending Videos|Automation and Tableau|📺📈 Analyzing trending-video history on YouTube for the advertising agency, to determine what content deserves marketing attention *(includes Tableau [dashboard](https://public.tableau.com/app/profile/sasha.fridman/viz/TrendingVideos_17052410546960/Dashboard?publish=yes) and [presentation]() of the project)*|Tableau, Canva|

### Description:

As video ad analysts at Sterling & Draper, we analyze trending YouTube videos to determine which content deserves marketing attention. Each video is categorized (Entertainment, Music, News & Politics, etc.), includes region info, and can trend for multiple days.

Every week, new employees ask:

- what video categories trended last week?
- how were they distributed among regions?
- which categories were popular in the U.S.?

To automate this, we’re creating a dashboard. After consulting with managers and database admins, we have the following requirements:

**Business goal:** analyze trending YouTube videos

**Usage frequency:** daily

**Users:** video ads planning managers

**Dashboard content:**
- trending videos by day and category
- trending videos by country
- correspondence table of categories and countries

**Data grouping:**
- date and time
- category
- country

**Data details:**
- trending history (absolute and percentage values)
- events by country (% values)
- category-country correspondence (table)

**Importance:** all graphs are equally important

**Data source:** an aggregate table (trending_by_time .csv)

**Update interval:** every 24 hours

Here you will find the project **[dashboard](https://public.tableau.com/app/profile/sasha.fridman/viz/TrendingVideos_17052410546960/Dashboard?publish=yes)** and **[presentation]().**
