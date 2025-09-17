# Course Reviews Sentiment — Naive Bayes (TF-IDF)

End-to-end notebook for predicting **good vs. bad sentiment** from user **course reviews** using **TF-IDF features** and a **Multinomial Naive Bayes** classifier.  
Includes text cleaning, quick EDA, basic class-imbalance handling, and clear evaluation with reports & confusion matrices.

> Main notebook: `User-Reviews-Naive-Bayes-Sentiment-Analysis.ipynb`

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Data](#data)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Quick Start](#quick-start)
- [How It Works](#how-it-works)
- [Results & Evaluation](#results--evaluation)
- [Use With Your Own Data](#use-with-your-own-data)
- [Troubleshooting](#troubleshooting)
- [Roadmap](#roadmap)
- [License](#license)

---

## Overview

This project takes raw user course reviews (free-text + rating), cleans them, explores rating patterns, converts text into TF-IDF vectors, and trains a **Naive Bayes** model to classify sentiment:

```text
good := rating >= 4
bad  := rating <  4
