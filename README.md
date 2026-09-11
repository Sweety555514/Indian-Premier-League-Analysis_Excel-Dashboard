

#IPL Analysis Dashboard — Advanced Excel

Project Overview

An interactive Indian Premier League (IPL) Analysis Dashboard created using Microsoft Excel to analyze team, player, venue, toss, and season-wise performance.

The dashboard covers 11 IPL seasons (2008–2018) and presents key insights through interactive charts and visualizations.

📊 Key Analysis

🏆 11 IPL Seasons analyzed from 2008–2018
🏏 Team Wins — Bat First vs Field First
🪙 Toss Decision vs Match Winning
🏟️ Top 10 Venues by Matches & Wins
⭐ Top 10 Man of the Match Players
👑 IPL Title Winners across 6 Teams
🏆 Season Winner & Runner-Up
⭐ Player of the Series

Project Highlights

Metric	Value
IPL Seasons Analyzed	11
Years Covered	2008–2018
Top Venues	10
Top MoM Players	10
Teams with IPL Titles	6
Dashboard	Interactive

Excel Skills Used

PivotTables & PivotCharts
GETPIVOTDATA
VLOOKUP + MATCH
Excel Tables & Structured References
Dynamic data retrieval
Data visualization
Dashboard design
Data analysis


Important Formulas

GETPIVOTDATA

=GETPIVOTDATA("player_of_match",$A$3,"player_of_match",A4)

Used to dynamically retrieve values from a PivotTable.

VLOOKUP + MATCH

=VLOOKUP($D$4,Table24[#All],MATCH(E3,Table24[#Headers],0),0)

Used for dynamic lookup, where MATCH identifies the required column based on its header


💡 Key Insight

The dashboard makes it easy to compare team performance, toss decisions, venue trends, player performance, and IPL championship history without going through large amounts of raw match data.

🎯 Project Objective

The objective was to transform raw IPL match data into a simple, interactive and visually appealing dashboard using Advanced Excel techniques.


📷 Dashboard Preview
https://github.com/Sweety555514/Indian-Premier-League-Analysis_Excel-Dashboard/blob/main/Dashboard.png

📚 Key Learning

This project helped me strengthen my skills in:

Advanced Excel | Data Analysis | PivotTables | Lookup Functions | Data Visualization | Dashboard Development

 Connect With Me

LinkedIn: www.linkedin.com/in/sweety-sinha-8a91622b3
