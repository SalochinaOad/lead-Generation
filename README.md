# Lead Generation Project
### Project Overview
This project aims to analyze web traffic data to understand patterns behind lead generation — the process of converting website visitors into potential customers. The analysis is grounded in the concept of a sales funnel, where visitors progress through various stages before converting into leads. By identifying key behavioral and demographic patterns, businesses can optimize their marketing strategies and improve conversion rates.

### Objectives
- Understand user behavior (e.g., mobile usage, page views, return visits)

- Examine traffic sources (Facebook, Taboola, Adwords, etc.)

- Identify factors that contribute to lead generation

- Create visual insights to assist marketing and business teams

### Dataset Description
Size: 287,742 observations with 6 features

### Features:

- source: Marketing source (Adwords, Facebook, etc.)

- returning: Whether the visitor is returning (1) or new (0)

- mobile: Accessed from mobile device (1) or not (0)

- country: Country of origin (US, UK, Canada)

- pages_viewed: Number of pages viewed during the session

- lead: Whether the visitor became a lead (1) or not (0)

### Key Insights
Majority of traffic comes from Facebook, but conversion rates vary by source.

Returning visitors and more pages viewed correlate with a higher probability of becoming leads.

Users from the US form the largest share of visitors but may not be the most efficient lead generators.

### Data Exploration & Visualization
Distribution plots and bar charts were created to visualize the frequency of leads by source, country, device type, and return status.

Histograms and bar plots reveal how pages_viewed differs between leads and non-leads.

Factor plots provide a deeper look at multi-variable relationships such as country, returning, and pages_viewed.

