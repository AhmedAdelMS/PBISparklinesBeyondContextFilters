# PBI Sparklines Beyond Context Filters

![Project Image](PBISparklinesBeyondContextFilters.png)

> Tinkering with the new Power BI Sparklines (In Preview) to test techniques to have sparklines go beyond table context filters

---

### Table of Contents
- [Description](#description)
- [References](#references)
- [Installation](#installation)

---
## Description
Power BI team released a preview of the much-awaited Sparklines feature in Table and Matrix Visuals. Tnkering with it, i stumbled upon Ed Hansberry's blog post about how to override context filters for sparklines. This was helpful but I then bumped into a special case where my table visual had a narrow filter applied (One Month) and I needed to get the sparklines to show different types of historical performance alongside (All history, Trailing three months...etc.). After a few initial failed attempts, found a simple solution of having a simple external date table (or anything you want your sparklines to pivot on) and use that as the pivot in the DAX measures for the sparklines. Hope you find it useful.
---
## References
- [Ed Hansberry's blog post](https://www.ehansalytics.com/blog/2021/12/8/working-with-sparklines-in-power-bi-all-about-the-filter-context)

---
## Installation
If you want to take this further, download files a local folder and change the source path for the Transactions.xlsx file in the Transactions query to point to your new location.
