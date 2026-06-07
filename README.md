📣 Meta Paid Ads Performance & ROAS Dashboard

A single-page Meta Paid Ads Performance & ROAS Dashboard built in Power BI, tracking campaign effectiveness across Facebook and Instagram. Covers impressions, clicks, conversions, engagement trends, audience demographics, and ad-type performance — with dynamic filtering by campaign, month, and target interest.


📸 Dashboard Preview
Show Image

📌 Project Overview
This dashboard gives marketers a complete picture of Meta ad campaign performance, enabling data-driven budget decisions and creative strategy. It combines high-level KPIs with granular breakdowns by ad type, audience demographics, geography, and time — all in a single interactive view.
The dashboard is designed for Instagram and Facebook campaigns, with slicers for dynamic metric switching, campaign filtering, and interest-based audience segmentation.

📊 KPIs at a Glance
MetricValueImpressions216.0KClicks25.4KShares1.3KPurchases1.3KEngagements29.3KComments2.6KCTR (Click-Through Rate)11.76%Engagement Rate13.56%Conversion Rate5.21%Purchase Rate0.61%Total Budget$2.5MAvg. Budget Per Campaign$50.7K

🗂️ Dashboard Sections
📍 Top KPI Cards
Two rows of KPI cards give an instant snapshot of campaign reach, engagement, and financial performance — covering both volume metrics (impressions, clicks, purchases) and rate metrics (CTR, conversion rate, engagement rate).

👥 Audience Demographics
Engagements by Gender

Female: 43%
Male: 22%
All (unspecified): 35%

Engagements by Age

Bar chart showing engagement distribution across age groups (teens to 50+)
Peak engagement concentrated in the 20–30 age range


🗺️ Engagements by Country
An interactive Bing Map visual plots engagement volume geographically, enabling regional performance analysis across North America, Europe, Asia, and beyond.

📅 Analysis by Month
A calendar-style matrix (navigable by month) shows daily performance data across the week — supporting time-based pattern recognition for scheduling and budget pacing decisions. Currently filtered to May.

📈 Engagement Trends
Weekly Engagements Trend

Stacked bar chart segmented by ad type: Carousel, Image, Stories, Video
Tracks weekly engagement volume across the month

Hourly Engagements Trend

Area/line chart showing engagement distribution by hour of day
Identifies optimal posting and ad-serving windows (peak activity visible around hours 5–15)


🎯 Analysis By Ad Type
Performance breakdown across the four ad formats:
Ad TypeImpressionsClicksCTRPurchase RateConv. RateEng. RateCarousel12.8K1.6K12.33%0.58%4.70%14.08%Image13.7K1.6K11.88%0.44%3.74%13.76%Stories19.1K2.3K11.77%0.70%—13.60%Video12.3K1.4K11.56%0.59%5.12%13.34%

🎛️ Interactive Filters (Slicers)

Dynamic Measure Selector — Switch the main metric displayed (Engagements, Clicks, Impressions, etc.)
Campaign Name — Filter all visuals by specific campaign
Target Interest — Segment data by audience interest category


🔑 Key Insights

Stories ads drive the highest impressions (19.1K) and clicks (2.3K), making them the top reach-generating format.
Carousel ads lead in Engagement Rate (14.08%), suggesting they drive the most interactive audience behavior.
Video ads deliver the highest Conversion Rate (5.12%), indicating stronger purchase intent among viewers.
Female audiences account for 43% of engagements — the largest single demographic segment.
The 20–30 age group shows the highest engagement concentration, key for targeting strategy.
CTR of 11.76% across all campaigns indicates strong ad relevance relative to typical industry benchmarks.
Hourly trends reveal clear peak engagement windows, useful for ad scheduling optimization.
Total budget of $2.5M spread across campaigns at an average of $50.7K per campaign.


🛠️ Tools & Technologies
ToolPurposePower BI DesktopDashboard design and report authoringDAXCalculated measures, KPIs, dynamic metric switchingPower Query (M)Data transformation and cleaningBing MapsGeographic engagement visualizationExcel / CSVSource data

📁 Repository Structure
meta-paid-ads-roas-dashboard/
│
├── 📊 Meta_PaidAds_ROAS_Dashboard.pbix    # Main Power BI report file
├── 📁 data/                                # Raw / cleaned source data (CSV/Excel)
├── 📁 screenshots/                         # Dashboard screenshots
│   └── Dashboard_roas.png
└── 📄 README.md

🚀 How to Use

Clone the repository

bash   git clone https://github.com/your-username/meta-paid-ads-roas-dashboard.git

Open the .pbix file in Power BI Desktop (free download).
If prompted, update the data source path to your local /data folder via:
Home → Transform Data → Data Source Settings
Click Refresh to reload all visuals.
Use the slicers on the right panel to filter by Dynamic Measure, Campaign Name, or Target Interest.
