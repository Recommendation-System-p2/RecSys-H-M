# 🛍️ Recsys H&M - Personalized Fashion Recommendations

![License](https://img.shields.io/github/license/Recommendation-System-p2/RecSys-H-M)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Kaggle](https://img.shields.io/badge/Kaggle-H%26M%20RecSys-green)

This repository contains my end-to-end solution for the [H&M Personalized Fashion Recommendations](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations) Kaggle competition. The goal is to recommend fashion articles to customers based on their purchase history.

---

## Table of Contents

- [🛍️ Recsys H\&M - Personalized Fashion Recommendations](#️-recsys-hm---personalized-fashion-recommendations)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Dataset](#dataset)
  - [Approaches](#approaches)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Models](#models)

---

## Overview

H&M Group provided 3 months of real-world transaction data (~30M records) to build a personalized recommender system based on data from previous transactions, as well as from customer and product meta data. The available meta data spans from simple data, such as garment type and customer age, to text data from product descriptions, to image data from garment images.

---

## Dataset

The dataset contains:

- `transactions_train.csv`: All purchase events by customers.
- `articles.csv`: Metadata about each product (e.g., product type, color, category).
- `customers.csv`: Customer-level features (age, fashion preference).
- `images/`: Image data for articles (optional use).

All data is available on the [Kaggle competition page](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data).

---

## Approaches

The pipeline includes:

- **Data Preprocessing**: Cleaning, filtering, deduplication.
- **EDA**: Customer behavior trends, seasonal effects, category-wise purchase frequencies.

---

## Exploratory Data Analysis

- Customer segmentation by age, activity, purchase frequency.
- Article metadata exploration: categories, seasons, colors, and styles.
- Temporal purchase trends and peak shopping periods.
- Item co-purchase heatmaps and session patterns.

---

## Models

- Will start with a baseline model.