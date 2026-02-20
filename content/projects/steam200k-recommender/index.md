---
title: "Steam-200k Recommender System (Implicit ALS)"
date: 2025-11-15
draft: false

summary: "Built a Top-N recommender using implicit-feedback ALS on the Steam-200k dataset, learning player preference profiles from gameplay behavior and recommending similar games."

tags: ["Data"]

image:
  filename: featured.png

links:
  - name: "Code"
    url: "https://github.com/dhruvsaikia/GameStoreRecommender"

external_link: ""
---

## Overview
This project builds a Top-N game recommendation tool using the Steam-200k dataset. It models user-game interactions and recommends games based on similarity between player profiles.

## What I built
- Implemented a recommender pipeline using implicit-feedback ALS (Alternating Least Squares).
- Transformed gameplay behavior into user preference signals to create user profiles.
- Generated Top-N recommendations by identifying players with similar profiles and surfacing games they play that the user hasn’t seen.

## Approach
- Treat play behavior as implicit feedback rather than explicit ratings.
- Learn latent factors for users and games using ALS.
- Recommend games with the highest predicted relevance for each user.

## Tools & tech
Python, implicit ALS, matrix factorization, data preprocessing, evaluation/validation

## Outcome
A working recommendation tool that produces personalized Top-N suggestions from large-scale interaction data.

---