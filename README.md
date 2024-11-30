# CS210-Project
# A Yearly Comparison of YouTube Watching Patterns: 2023 vs. 2024

## Dataset Description
The dataset is my personal YouTube watch history exported from Google Takeout. It provides insights into my viewing habits over the years 2023 and 2024. The dataset includes:
- **Timestamps:** The exact date and time when each video was watched.
- **Titles and URLs:** Video metadata that allows content classification.
- **Channel Names:** Information about the creators of the videos I watched.

### Key Details:
- **Time Range:** February 14, 2023, to the present.
- **Source:** Google Takeout YouTube watch history JSON file.
- **Limitations:**
  - Older data before February 2023 is unavailable due to account settings.
  - Missing metadata for private or deleted videos might slightly affect analysis.

---

## Project Idea
The goal of this project is to analyze and compare my YouTube watching patterns over 2023 and 2024. By exploring my recent viewing habits, I aim to uncover:
1. **Temporal Trends:** Differences in viewing activity by time of day, day of the week, and month between the two years.
2. **Content Preferences:** Shifts in the types of videos I watched, such as genres or channels.
3. **Engagement Patterns:** Changes in binge-watching behavior and the diversity of content consumed.

This analysis will reflect how my media consumption habits have evolved over time, providing actionable insights into my viewing behavior.

---

## Project Plan

### 1. Data Preparation
- Clean and preprocess the YouTube JSON file (`izleme_gecmisi.json`).
- Extract relevant fields such as timestamps, video titles, and channels.
- Convert timestamps into usable formats (e.g. weekdays, months).

### 2. Analysis
#### Temporal Trends:
- Analyze hourly, daily, and monthly activity for both years.
- Compare usage patterns on weekdays vs. weekends.

#### Content Preferences:
- Classify videos into genres using keywords or metadata.
- Identify top genres and channels for 2023 and 2024.
- Analyze shifts in genre preferences and channel popularity.

#### Engagement Patterns:
- Detect binge-watching sessions (e.g., 3+ consecutive videos watched within an hour).
- Assess the diversity of genres and channels consumed in each year.

### 3. Visualization
- Create heatmaps for temporal trends (hourly and daily activity).
- Use bar charts and line graphs to compare genres and channels across years.
- Plot binge-watching frequency and content diversity metrics.

### 4. Documentation
- Summarize key findings and visualizations in the final report.
- Host all analysis and code in a structured GitHub repository.

---

## Repository Structure
