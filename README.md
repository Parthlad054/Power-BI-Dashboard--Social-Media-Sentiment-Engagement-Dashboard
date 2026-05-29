# 📊 Social Media Sentiment & Engagement Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Data%20Analytics-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Social%20Media-E1306C?style=for-the-badge&logo=instagram&logoColor=white" />
  <img src="https://img.shields.io/badge/NLP%20%7C%20Sentiment-00B050?style=for-the-badge&logo=openai&logoColor=white" />
</p>

> An interactive Power BI dashboard that analyzes social media sentiment, engagement, and virality across multiple platforms — empowering marketers and analysts to make data-driven decisions.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Live KPIs](#-live-kpis)
- [Dashboard Features](#-dashboard-features)
- [Platforms Covered](#-platforms-covered)
- [Visualizations](#-visualizations)
- [Filters & Interactivity](#-filters--interactivity)
- [File Structure](#-file-structure)
- [How to Use](#-how-to-use)
- [Tech Stack](#-tech-stack)
- [Key Insights](#-key-insights)
- [Author](#-author)

---

## 🧭 Overview

The **Social Media Sentiment & Engagement Dashboard** is a comprehensive Power BI report built to track and visualize how content performs across major social media platforms. It combines **NLP-based sentiment scoring**, **engagement metrics**, and **virality analysis** into a single, unified view — helping teams understand what resonates with audiences and when.

Whether you're a social media manager, digital marketer, or data analyst, this dashboard provides a 360° view of your brand's online presence.

---

## 📈 Live KPIs

| Metric | Value |
|---|---|
| 📝 Total Posts Analyzed | **500** |
| 💬 Total Engagement | **396 Million** |
| 📊 Engagement Rate | **20.06%** |
| 🔁 Avg Virality Score | **5.07** |
| 😐 Avg Sentiment Score | **0.02** (Near Neutral) |

---

## ✨ Dashboard Features

- ✅ **Sentiment Classification** — Posts categorized as Positive, Neutral, or Negative
- ✅ **Platform Benchmarking** — Side-by-side comparison across 5 major platforms
- ✅ **Virality Trend Analysis** — Time-series trends by month and timestamp
- ✅ **Media Type Breakdown** — Image vs. Video performance comparison
- ✅ **Geographic Mapping** — World map showing engagement distribution by country
- ✅ **Dynamic Slicers** — Filter by hashtag, topic category, and country
- ✅ **Monthly Trend Lines** — Sentiment trends across platforms over time

---

## 🌐 Platforms Covered

| Platform | Color Code |
|---|---|
| 🔵 Facebook | Blue |
| 🟣 Instagram | Purple/Pink |
| 🟠 LinkedIn | Orange |
| 🟪 TikTok | Dark Purple |
| ⬛ X (Twitter) | Dark / Black |

---

## 📊 Visualizations

### 1. 📉 Engagement & Virality Over Time
A dual-axis line chart showing **Total Engagement** and **Avg Virality Score** plotted against post timestamps and months — revealing posting patterns and peak engagement periods.

### 2. 🍩 Post Type Distribution (Pie Chart)
Breakdown of sentiment-classified posts:
- 🔵 **Negative Posts** — 165 (33%)
- 🔴 **Positive Posts** — 173 (34.6%)
- 🟤 **Neutral Posts** — 162 (32.4%)

### 3. 🔵 Platform Scatter Plot
Scatter chart comparing **Count of Sentiment Score** vs **Total Engagement** by platform, with bubble size representing **Sum of Virality Score** — quickly identifying top-performing platforms.

### 4. 📊 Media Type Distribution (Bar Chart)
Compares total post counts by media type: **Image** vs **Video**, revealing which format generates more content volume.

### 5. 🗺️ Geographic Engagement Map
An interactive world map displaying regional engagement concentration, helping identify key markets and underserved regions.

### 6. 📈 Monthly Sentiment Trends (Multi-Platform Line Chart)
Platform-specific sentiment trend lines across all months — track how brand perception evolves over time per channel.

---

## 🎛️ Filters & Interactivity

The dashboard supports the following dynamic slicers:

| Slicer | Options |
|---|---|
| `hashtags` | All / Specific hashtag |
| `topic_category` | All / Specific topic |
| `country` | All / Specific country |
| `platform` (chart-level) | Facebook, Instagram, LinkedIn, TikTok, X |

> All visuals are cross-filtered — clicking any data point updates the entire dashboard in real time.

---

## 📁 File Structure

```
📦 social-media-sentiment-dashboard/
├── 📊 dashboard.pbix          # Power BI source file (editable)
├── 📄 dashboard_1.pdf         # Static PDF snapshot of the dashboard
└── 📝 README.md               # Project documentation (this file)
```

---

## 🚀 How to Use

### Prerequisites
- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Free) — version 2.x or above

### Steps

1. **Clone or download** this repository
   ```bash
   git clone https://github.com/your-username/social-media-sentiment-dashboard.git
   ```

2. **Open the `.pbix` file** in Power BI Desktop
   ```
   File → Open → dashboard.pbix
   ```

3. **Refresh Data** (if connected to a live source)
   ```
   Home → Refresh
   ```

4. **Interact with slicers** — Use the hashtag, topic, and country filters to explore specific segments

5. **Publish to Power BI Service** (optional)
   ```
   Home → Publish → Select Workspace
   ```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development & DAX measures |
| **DAX (Data Analysis Expressions)** | Custom KPI calculations |
| **Power Query (M Language)** | Data transformation & cleaning |
| **Bing Maps / TomTom** | Geographic visualization |
| **NLP Sentiment Scoring** | Text-based sentiment classification |

---

## 💡 Key Insights

- 📣 **Positive posts slightly outperform** neutral and negative in volume (34.6%), suggesting an overall favorable brand tone
- 🔥 **TikTok and LinkedIn** show higher virality scores relative to their engagement volume — indicating strong organic reach
- 🖼️ **Image content** leads in total post count, though video content merits further ROI comparison
- 🌍 **Engagement is geographically concentrated** in North America and Europe, with potential growth in Asia and South America
- ⏰ **Peak engagement timestamps** vary across months, indicating the importance of platform-specific scheduling strategies

---

## 👤 Author

**Your Name**
📧 your.email@example.com
🔗 [LinkedIn](https://linkedin.com/in/your-profile) | [GitHub](https://github.com/your-username)

---

## 📃 License

This project is licensed under the [MIT License](LICENSE) — free to use, modify, and distribute with attribution.

---

<p align="center">
  ⭐ If you found this project helpful, please consider giving it a star!
</p>
