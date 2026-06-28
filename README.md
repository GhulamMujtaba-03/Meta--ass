# # Meta Ad Performance Dashboard

## Project Overview 📌
- This project focuses on building an interactive, production-grade Power BI dashboard utilizing advertising campaign data from Meta platforms (Facebook and Instagram).
- The objective was to consolidate multi-channel performance data into a unified business intelligence solution, allowing stakeholders to track real-time campaign performance, optimize budget allocation ($2.5M total budget), evaluate creative ad structures, and analyze audience behavior patterns to improve conversion metrics.

## Project Objectives 🎯
- Build an interactive, comprehensive 2-page Power BI dashboard for Meta Ads tracking.
- Create dynamic measures using complex DAX calculations for cross-channel analysis.
- Provide deep insights into audience demographic distribution (Age & Gender).
- Monitor spending efficiency through precise CTR, Conversion Rate, and Purchase Rate metrics.
- Analyze temporal trends (Hourly and Weekly) to streamline ad scheduling and maximize ROAS.

## Tools & Technologies 🛠️
### Data Analysis & Modeling
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (M Language)

---

## Power BI Dashboard 📊
### The dashboard consists of 2 interactive pages designed to analyze different slices of Meta campaign data.

#### Page 1: Overall & Instagram Performance View 📈
![Instagram_Analysis](14549.png)

###### KPIs
- **Impression:** 216.0K
- **Clicks:** 25.4K
- **Shares:** 1.3K
- **Comments:** 2.6K
- **Purchases:** 1.3K
- **Engagement:** 29.3K
- **CTR (Click-Through Rate):** 11.76%
- **Engagement Rate:** 13.56%
- **Conversion Rate:** 5.21%
- **Purchase Rate:** 0.61%
- **Total Budget:** $2.5M
- **Avg Budget/Campaigns:** $50.7K

###### Slicers
- Platform Toggles (Facebook / Instagram)
- Select Dynamic Measure (Engagement, Clicks, etc.)
- Campaigns Name
- Target Interest
- Month Selection Matrix (Calendar View)

###### Visualizations
- **engagement by Gender:** Donut chart breakdown showing Female (12.7K / 43%), Male (6.4K / 22%), and All (10.2K / 35%).
- **engagement by Age:** Frequency distribution bar chart tracking age buckets from 15 to 50+.
- **Weekly engagement Trend:** Stacked bar chart highlighting weekly progression distribution.
- **Hourly engagement Trend:** Continuous area chart tracking performance spikes within a 24-hour cycle.
- **Analysis By Ad Type:** Heatmap matrix table comparing Video, Carousel, Image, and Stories across IMPR, CLKS, CTR, PR, ER, and CR.

###### Business Insights
- High volume baseline configuration when evaluating across overall blended campaign structures.
- Peak consumer engagement is highly driven by the Female demographic segment (43%).
- Stories and Carousel ad types lead in click-through volumes, signaling high asset resonance.

---

#### Page 2: Facebook Performance View 👥
![Facebook_Analysis](14547.png)

###### KPIs
- **Impression:** 123.8K
- **Clicks:** 14.7K
- **Shares:** 682.0
- **Comments:** 1.5K
- **Purchases:** 708.0
- **Engagement:** 16.8K
- **CTR (Click-Through Rate):** 11.86%
- **Engagement Rate:** 13.60%
- **Conversion Rate:** 4.82%
- **Purchase Rate:** 0.57%
- **Total Budget:** $2.5M
- **Avg Budget/Campaigns:** $50.7K

###### Slicers
- Platform Toggles (Facebook / Instagram)
- Select Dynamic Measure (Engagement, Clicks, etc.)
- Campaigns Name
- Target Interest
- Month Selection Matrix (Calendar View)

###### Visualizations
- **engagement by Gender:** Donut chart breakdown showing Female (6.2K / 37%), Male (4.5K / 27%), and All (6.2K / 37%).
- **engagement by Age:** Detailed age-group volume breakdown mapping prime-converting target brackets.
- **Weekly engagement Trend:** Color-coded structural bars displaying consistency drops or increases per week.
- **Hourly engagement Trend:** 24-Hour peak activity line tracking exactly when Facebook ads are triggering traction.
- **Analysis By Ad Type Matrix:** Structural metric evaluation for Carousel, Image, Stories, and Video.

###### Business Insights
- Facebook drives a higher concentration of blended multi-action audiences compared to isolated platform views.
- Ad Type matrix shows that static Images maintain a highly robust CTR (12.17%) on Facebook feeds compared to other asset types.
- Clear structural drop-offs can be targeted by adjusting scheduling parameters on specific off-peak hourly trend windows.

---

## Data Model & DAX Logic Overview 📐
- Optimized star schema or flat table structures engineered inside Power Query.
- Custom dynamic formatting rules implemented to swap underlying datasets using metric parameters without layout breakdown.

### Author 👨‍💻
- Ghulam Mujtaba
