# AI Recommendation System

A simple recommendation engine built as part of an AI internship project.
Includes two approaches:

## 1. Tag-Based Recommendation (`recommend_tags.py`)
Uses Jaccard similarity to match user-entered interests against movie tags.

**Run it:**
\`\`\`
python recommend_tags.py
\`\`\`

## 2. Rating-Based Recommendation (`recommend_ratings.py`)
Uses cosine similarity (collaborative filtering) to compare a new user's
ratings against existing users, then recommends unrated movies liked by
similar users.

**Run it:**
\`\`\`
python recommend_ratings.py
\`\`\`

## Requirements
- Python 3.x (no external libraries needed)

## Concepts Used
- Jaccard similarity
- Cosine similarity
- Basic collaborative filtering
