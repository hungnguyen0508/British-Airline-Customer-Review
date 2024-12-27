# British Airways Customer Review Analysis

This repository contains the analysis of customer feedback for British Airways, sourced from Skytrax. The primary objective is to extract meaningful insights from textual data through web scraping, data cleaning, sentiment analysis, and topic modeling. This project is powered by Python and state-of-the-art machine learning techniques.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Methods and Tools](#methods-and-tools)
3. [Key Features](#key-features)
4. [Findings and Insights](#findings-and-insights)
5. [Usage](#usage)
6. [Requirements](#requirements)
7. [License](#license)

---

## Project Overview

British Airways (BA) is the flag carrier airline of the United Kingdom, handling thousands of flights daily. This project analyzes BA customer reviews sourced from Skytrax to understand their sentiments, major concerns, and experiences. The report aims to provide actionable insights to enhance customer satisfaction by:

- Identifying common themes in feedback.
- Assessing sentiment across different seat classes and traveler types.
- Evaluating the relationship between service areas and customer attitudes.

---

## Methods and Tools

### 1. **Web Scraping**
   - Extracted customer reviews from the Skytrax website using Python's scraping libraries.

### 2. **Data Cleaning**
   - Processed raw text to remove noise and prepare it for analysis.

### 3. **Sentiment Analysis**
   - Applied the **RoBERTa model**, a transformer-based deep learning model, to determine the sentiment polarity (positive, negative, neutral) of customer reviews.

### 4. **Topic Modeling**
   - Utilized **Latent Dirichlet Allocation (LDA)** to identify and categorize major discussion themes in the feedback:
     - **In-Flight Services**
     - **Flight Operations and Punctuality**
     - **Onboard Dining and Amenities**
     - **Customer Service and Support**

---

## Findings and Insights

### Analytical Highlights:
1. **Seat Class and Sentiment**
   - Economy Class reviews dominate (54.3%), with the highest proportion of negative feedback.
   - First Class passengers report the highest satisfaction levels (~40% positive feedback).

2. **Service Area and Sentiment**
   - **In-Flight Services** and **Flight Operations** receive the most negative feedback, particularly from Economy Class.
   - Premium classes (Business and First) show fewer complaints, indicating better satisfaction.

3. **Traveler Purpose and Sentiment**
   - Leisure travelers account for the majority of reviews, with family travelers showing the most dissatisfaction.
   - In-Flight Services are a critical concern for family leisure customers.

4. **Topic Discussion by Attitude**
   - Negative reviews dominate across topics, highlighting significant areas for improvement, especially for Economy Class and family leisure travelers.

For a detailed analysis, refer to the full report included in this repository.

---

