# Thumbnail Colorfulness vs Click Rate: A Behavioral Analysis

This project investigates the relationship between thumbnail image colorfulness and user engagement—specifically click-through rate—on video content hosted on weather.com.

## 📌 Purpose

The goal was twofold:
1. Explore TWCo's Amplitude and CMS tooling via a hands-on data science project.
2. Determine whether visual features, like colorfulness, influence user engagement before publishing content.

## 🔬 Research Foundation

This project uses Hasler and Süsstrunk's 2003 method to quantify the "colorfulness" of an image and correlates it with Amplitude-sourced click behavior.

## 🧪 Methodology

- **Data Cleaning**: Parsed Amplitude metrics for page views and video plays, computed conversion rates.
- **Web Scraping**: Collected video thumbnail URLs from live content pages using BeautifulSoup.
- **Image Analysis**: Calculated a quantitative colorfulness score for each thumbnail using OpenCV.
- **Statistical Analysis**: Used Pearson correlation to explore the relationship between click rate and colorfulness.

## 📈 Results

- **Correlation (r):** -0.3261
- **r²:** 0.1063
- **P-value:** 1.319e-20  
- **Sample Size:** 773 out of 1000 entries

## 📚 Report

- The full link to the report can be found [here]([url](https://docs.google.com/document/d/1zcmSVYVmVQ2QLdSVP9JOtWVX3iHA-2AL9eAJN5dZYl0/edit?tab=t.bn23an2ws9og)).

## 📂 Repository Structure

See the folders for notebooks, reusable code, and outputs. Each step is clearly documented.

## 🔧 Requirements

```bash
pip install -r requirements.txt
