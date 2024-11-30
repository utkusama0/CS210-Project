# CS210-Project  
# A Yearly Comparison of YouTube Watching Patterns: 2023 vs. 2024

---

## Dataset Description
The dataset is my personal YouTube watch history exported from Google Takeout. It provides detailed insights into my viewing habits over the years 2023 and 2024. Key data fields include:
- **Timestamps:** The exact date and time when each video was watched.
- **Titles and URLs:** Metadata for content classification and analysis.
- **Channel Names:** Information about the creators of the videos I watched.

### Key Details:
- **Time Range:** February 14, 2023, to the present.
- **Source:** Google Takeout YouTube watch history JSON file (`izleme_gecmisi.json`).
- **Limitations:**
  - Older data before February 2023 is unavailable due to account settings.
  - Missing metadata for private or deleted videos may slightly affect analysis.

---

## Research Question
**"How have my YouTube watching patterns, including temporal habits, content preferences, and engagement trends, evolved between 2023 and 2024?"**

---

## Project Idea
The goal of this project is to analyze and compare my YouTube watching patterns over 2023 and 2024. By exploring my recent viewing habits, I aim to uncover insights into:
1. **Temporal Trends:** Differences in viewing activity by time of day, day of the week, and month between the two years.
2. **Content Preferences:** Shifts in the types of videos I watched, such as genres or channels.
3. **Engagement Patterns:** Changes in binge-watching behavior and the diversity of content consumed.

This analysis will help reflect how my media consumption habits have evolved over time and provide actionable insights into my viewing behavior.

---

## Project Plan

### 1. Data Preparation
- Load and clean the YouTube JSON file (`izleme_gecmisi.json`).
- Extract relevant fields such as timestamps, video titles, and channel names.
- Convert timestamps into usable formats (e.g., weekdays, months, hours).

### 2. Analysis
#### Temporal Trends:
- Analyze viewing activity by:
  - **Hour of the Day:** Identify peak times for YouTube usage.
  - **Day of the Week:** Compare weekday vs. weekend activity.
  - **Monthly Trends:** Track how habits change over months in both years.

#### Content Preferences:
- Classify videos into genres using keywords or metadata.
- Identify top genres and channels for each year.
- Compare the shifts in genre preferences and channel popularity between 2023 and 2024.

#### Engagement Patterns:
- Detect binge-watching sessions (e.g., 3+ consecutive videos watched within an hour).
- Assess content diversity by calculating the number of unique genres and channels consumed in each year.

### 3. Visualization
- Create **heatmaps** to visualize hourly and daily activity patterns.
- Use **bar charts** and **line graphs** to compare genres and channels across years.
- Plot binge-watching frequency and content diversity metrics.

### 4. Documentation
- Summarize key findings in a report.
- Include visualizations for clear representation of insights.
- Host all analysis and code in a structured GitHub repository.

---

