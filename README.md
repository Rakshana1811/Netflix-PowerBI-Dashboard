Netflix User Analysis — Power BI Dashboard

This is a personal data analytics project I built using a Netflix user dataset. I wanted topractice the complete workflow — cleaning raw data directly in Power BI using PowerQuery, modeling it and designing dashboards that actually tell a story.
The dataset has 50,000 users across 10 countries, and I ended up building 5 dashboardpages covering everything from user demographics to how people find content to watch.

What I used:
1)Power Query (Power BI)— cleaned the raw CSV directly inside Power BI, handleddata types, nulls, and created extra columns
2)Power BI Desktop— data model, DAX measures, and all the visuals
3)Theme— went with a dark Netflix-style red and black theme throughout

The Dashboards:
Page 1 — User Overview
A general look at who the users are. The gender split is almost exactly 50/50, and about 83%of users are still active. USA has the most users, but all 10 countries are pretty close to eachother in numbers.

Page 2 — User Behaviour
This one looks at how people actually use the platform. Average watch time is 85 minutesper session. Most people use TV devices, and interestingly, night-time has the highestaverage watch time. I also added a liked/disliked breakdown here.

Page 3 — Content Performance
Thriller is the most watched genre, but Drama has the highest average watch time. Seriesare more popular than Movies overall. Completion rate is quite high at 91.92% whichsurprised me a bit.

Page 4 — Subscription Analysis
Standard plan brings in the most revenue even though Premium has more subscribers.Payment methods are split almost evenly three ways — Card, Wallet, and Bank Transfer.

Page 5 — Recommendation & Preferences
Trending content gets the most likes, but Friend recommendations are close behind. Dramaand Thriller top the ratings. Language preference is spread evenly which makes sense for aglobal dataset.

A few things I noticed in the data:
1)Most users (83%) are still active, so churn isn't a massive problem in this dataset
2)People who watch Series tend to spend more time on the platform than Moviewatchers
3)Night is when users are most engaged — makes sense
4)Thriller and Drama are consistently strong across every metric I looked at

Files in this repo

├── Netflix_project.pbix                  ← open this in Power BI Desktop
├── netflix_titles.csv                    ← the raw dataset
├── Screenshot_2026-06-13_134616.png      ← User Overview
├── Screenshot_2026-06-13_134905.png      ← User Behaviour
├── Screenshot_2026-06-13_134942.png      ← Content Performance
├── Screenshot_2026-06-13_135017.png      ← Subscription Analysis
└── Screenshot_2026-06-13_135044.png      ← Recommendation & Preferences
