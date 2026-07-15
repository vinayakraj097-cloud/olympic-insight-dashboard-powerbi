# 🏅 Olympic Insight Dashboard

An interactive Power BI dashboard analyzing over 120 years of Olympic history — covering countries, athletes, events, sports, and medal outcomes from the Summer and Winter Games.

![Dashboard Overview](screenshots/dashboard-overview.png)

## 📊 Overview

| Metric | Value |
|---|---|
| Total Countries | 207 |
| Total Athletes | 135K |
| Total Events | 765 |
| Sports Covered | 66 |
| Total Medals | 40K |
| Gold / Silver / Bronze | 13.4K / 13.1K / 13.3K |

## 🔍 Key Insights

- **USA dominates the medal table** — 5.6K medals, 43% more than Russia (#2) and 1.47x Germany (#3). The top 5 countries alone (USA, Russia, Germany, UK, France) account for ~43% of all medals despite being just 2.4% of participating nations.
- **Medal concentration by sport** — Athletics, Swimming, and Rowing together contribute ~25% of all medals from just 3 of the 66 sports tracked.
- **A remarkably balanced medal split** — Gold (33.6%), Silver (33.0%), and Bronze (33.4%) sit within 0.64 percentage points of each other, reflecting a clean, well-structured dataset.
- **Home-field advantage is measurable** — the USA earned 1,003 medals as host, more than double the Soviet Union's 488 as the next-highest host nation.
- **Standout individual performance** — the top athlete holds 28 medals, 55% ahead of the second-highest (18).
- **Participation has grown steadily since 1880**, with the sawtooth pattern reflecting alternating Summer/Winter Games, and the gender participation gap visibly narrowing in recent decades.

## 🛠️ Built With

- **Power BI** — data modeling, DAX measures, interactive visuals
- **Power Query** — data cleaning and transformation

## 📁 Repository Structure

```
olympic-insight-dashboard/
├── README.md
├── Olympic_dashboard.pbix
├── screenshots/
│   └── dashboard-overview.png
└── data/
    └── (dataset used, if shareable)
```

## ▶️ How to View

This dashboard was built in Power BI Desktop. To explore it interactively:
1. Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repo and open `Olympic_dashboard.pbix`
3. Use the filters (Year, Country, Sport, Season, Sex, Medal) to explore the data live

## 📌 About

Built by [Vinayak](https://github.com/vinayakraj097-cloud) as part of an ongoing data analytics portfolio.
