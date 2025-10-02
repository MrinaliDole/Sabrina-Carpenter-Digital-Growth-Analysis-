# Sabrina-Carpenter-Digital-Growth-Analysis

📌 Project Overview

As part of our Marketing Analytics course, our team explored how data-driven strategies influence digital virality in the entertainment industry. We analyzed the digital rise of pop artist Sabrina Carpenter across platforms (Spotify, TikTok, YouTube, Instagram) to answer a key question:

👉 Is virality truly organic, or can streaming success be engineered through strategic releases and brand collaborations?

📝 Concise Narrative Summary

Our team collected and analyzed two years of audience engagement data across major platforms to study the impact of singles, albums, and brand partnerships on Sabrina Carpenter’s digital growth. Using the Songstats API and manually compiled event timelines, we created a dataset of 30+ events. We applied 28-day pre/post spike analysis, OLS regression modeling, and sentiment analysis on YouTube comments to isolate the true impact of each event type.

The results showed that singles consistently outperformed albums, driving the biggest spikes in Spotify streams, TikTok views, and Shazams, while brand collaborations delivered mixed results. We found statistically significant audience lifts (+6.5M Spotify Monthly Listeners, +927M TikTok views, +683K Instagram followers) and discovered that sentiment trends didn’t always correlate with follower growth.

This project combined data engineering, time-series analysis, regression modeling, and NLP to reveal the anatomy of digital success in music marketing.

📦 Key Deliverables

Python Notebooks

Marketing_Analytics_Project_Data_Extraction.ipynb – API data extraction & event alignment

SC_Youtube_Sentiment_Analysis_v4_0.ipynb – NLP sentiment analysis using VADER

Dataset (Sabrina’s Journey.xlsx) – cleaned and integrated event + audience data

Presentation (Sabrina Carpenter Digital Growth.pdf) – executive deck with key findings

📊 Key Insights

Singles like Espresso and Please Please Please created the largest audience spikes (TikTok +11%, Shazams +7%).

Brand collaborations (Samsung, Dunkin’, Van Leeuwen Ice Cream) had mixed impact despite media buzz.

Regression models showed statistically significant audience lifts post-events:

+6.5M Spotify Monthly Listeners

+927M TikTok Views

+683K Instagram Followers

Average sentiment on YouTube: ~50% positive, ~35% negative, but follower spikes didn’t always mirror emotion.

🛠️ Tools & Methods

Data Sources: Songstats API, Google News (event timelines), YouTube comments

Python: pandas, matplotlib, seaborn, statsmodels, VADER NLP

Statistical Modeling:

28-day pre/post event spike analysis

OLS regression with event fixed effects

NLP: Sentiment analysis of YouTube comments using VADER

Visualization: Multi-platform time series plots, boxplots, spike overlays

🌍 Business Impact

Provided a framework for measuring marketing ROI in entertainment

Demonstrated how timing and content type (singles > albums) drive digital engagement

Showed that brand partnerships don’t guarantee virality, highlighting the importance of strategic alignment

Illustrated how analytics can separate hype from real impact in digital campaigns

🔬 Technical Depth 

Designed event-based time-series experiments (28-day rolling windows)

Built OLS regression models controlling for event-level variation

Engineered features for event classification (album, single, collab)

Scraped & analyzed 900K+ YouTube comments with VADER sentiment scoring

Normalized multi-platform metrics to compare momentum across Spotify, TikTok, YouTube, Instagram

📈 Dashboard / Visualization Highlights

Multi-platform audience timeline with event overlays

Boxplots comparing Singles vs Albums (clear outperformance of singles)

Regression tables quantifying post-event lifts

Sentiment charts showing polarity shifts across major events
