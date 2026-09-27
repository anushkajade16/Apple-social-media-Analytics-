# Apple Social Media Analytics

This project looks at Apple's social media performance across Instagram, Twitter, YouTube, and LinkedIn using a simulated dataset — built to practice real-world social media analytics using just Excel (pivot tables, charts, and some manual data wrangling).

I split the work into six parts, each in its own file, going from raw data to specific business questions.

## What's in each file

**Task 1 — Cleaning the data**
Started with a messy raw dataset of ~500 posts and cleaned it up: split combined hashtags into separate columns, standardized dates, and got it into a shape I could actually build pivot tables on.

**Task 2 — Engagement analysis**
Calculated engagement rate per post and pulled out the top 10 highest-engagement Apple posts. Also broke down performance by platform and content type using pivot tables.

**Task 3 — Platform analysis**
Compared weekly follower growth, unfollows, and engagement rate across platforms to see which ones were actually growing vs. just posting a lot.

**Task 4 — Hashtag & content strategy**
This is the one I found most interesting. #AppleEvent and #AppleWatch were the most-used hashtags overall, but when I looked at actual performance instead of just frequency, #iPhone16Launch#AppleEvent had the highest average likes — meaning it wasn't just used a lot, it actually worked. On the content side, Carousel and Video posts clearly outperformed Image posts, so if I were advising a real content calendar, I'd lean into carousels/video and use images as more of a supporting format, not the main push.

**Task 5 — Campaign effectiveness**
Looked at ad spend vs. impressions vs. engagement uplift across different campaigns (like the iPhone 16 launch and the MacBook Air M3 push) to see which campaigns actually gave good return relative to what was spent.

**Task 6 — Follower retention & loyalty**
Tracked follower growth week over week, smoothed it out with a moving average to see the real trend (not just weekly noise), and compared that against ad spend to see if paid spend was actually driving retained followers or just short-term bumps.

## Tools

Excel — pivot tables, pivot charts, and formulas. No Python or Power BI here, this one was purely about seeing how far you can push Excel for a full analytics workflow.

## Files

## Files

- [`task_1_cleaning_data.xlsx`](task_1_cleaning_data.xlsx) – raw data cleanup and formatting
- [`task_2_Engagement_analysis.xlsx`](task_2_Engagement_analysis.xlsx) – engagement rate calculations and top-performing posts
- [`task_3_Platform_analysis.xlsx`](task_3_Platform_analysis.xlsx) – platform-by-platform comparison of growth and engagement
- [`task_4_Hashtag_and_content_strategy.xlsx`](task_4Hashtag_and_content_statergy.xlsx) – hashtag frequency vs. performance, content type comparison
- [`task_5_Campaign_Effectiveness.xlsx`](task_5_Campaign_Effectiveness.xlsx) – ad spend vs. impressions vs. engagement uplift by campaign
- [`task_6_Follower_Retention_Loyalty.xlsx`](task_6_Follower_Retention___Loyalty.xlsx) – follower growth trends and retention vs. ad spend

I also recorded a short walkthrough explaining the approach and findings: [watch here](https://drive.google.com/file/d/1vxuDI7gyfCdOYUCexZ_9xbUqhLwLZvZf/view?usp=sharing)
