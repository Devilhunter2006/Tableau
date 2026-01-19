

Airways Customer Experience Analysis (Tableau)

Project Overview
This project analyzes airline customer satisfaction using interactive Tableau dashboards. Users can dynamically explore different service metrics such as Overall Rating, Cabin Staff Service, Food & Beverages, Entertainment, Seat Comfort, Ground Service, and Value for Money.
The objective is to identify key drivers of customer satisfaction and highlight areas for service improvement across airlines.

Tools & Technologies
Tableau Desktop / Tableau Public
Calculated Fields and Parameters
Data Visualization and Dashboard Design

Repository Contents
Airways Project varun.twbx – Packaged Tableau Workbook
README – Project documentation

Key Features
Dynamic metric selection using a parameter-driven calculated field
Interactive dashboards with filters for airline and service metrics
Customer satisfaction insights across multiple service dimensions

Example Calculated Field
CASE [Pick a metric]
WHEN 'Overall' THEN [Rating]
WHEN 'Cabin Staff Service' THEN [Cabin Staff Service]
WHEN 'Food' THEN [Food Beverages]
WHEN 'Entertainment' THEN [Entertainment]
WHEN 'Ground Service' THEN [Ground Service]
WHEN 'Seat Comfort' THEN [Seat Comfort]
WHEN 'Value' THEN [Value For Money]
END

How to Use
Download the Tableau packaged workbook (.twbx) from the repository
Open the file using Tableau Desktop or Tableau Public
Use the metric selector parameter to switch between service ratings
Analyze trends and compare airline performance

Insights You Can Discover
Service areas that most strongly influence overall ratings
Airlines performing best in specific service categories
Differences between customer expectations and perceived value

Future Enhancements
Time-based trend analysis
Sentiment analysis from customer reviews
Publishing the dashboard to Tableau Public

Author
Varun

---
