# InsightFeed-AI-Interest-Thread-Smart-Recommendation

## Overview

InsightFeed is an AI-powered recommendation agent that analyzes the Reels a student interacts with, understands their underlying interests, and recommends useful technology-related content.

Instead of relying only on keywords, InsightFeed considers **content context and user behavior** such as watch time, likes, replays, and skips.

## Problem

Students spend significant time scrolling short-form content. InsightFeed aims to make this existing scrolling more useful by recommending educational and career-focused technology content based on actual interests.

## Key Features

* AI-based interest inference
* Semantic understanding instead of simple keyword matching
* Watch, like, replay, and skip signals
* Broad interest detection
* Personalized technology recommendations
* Negative-signal handling for skipped content
* "Why you're seeing this" explanation
* Daily recommendation slot
* Reel watch/view functionality
* Safe fallback recommendation when AI fails

# Deploymentlink- https://insightfeed-refined.ai.studio
## Example

A student interacts with:

* Java interview meme
* Software engineer lifestyle Reel
* Coding interview meme
* Developer laptop comparison
* AI career-hype Reel — skipped
* Tech security news

InsightFeed should infer:

**Primary Interest:** Software Engineering / Technology
**Secondary Interest:** Technical Interviews / Developer Career

Instead of simply recommending another Java Reel.

## Technology Stack

* Frontend: HTML, CSS, JavaScript
* Backend: Python, Flask
* AI: Anthropic API
* Development: Replit

## How It Works

```text
Reel Interactions
       ↓
Behavior Analysis
       ↓
Semantic Understanding
       ↓
Interest Inference
       ↓
Negative Signal Filtering
       ↓
AI Recommendation
       ↓
Daily Recommended Reel
```

## Future Scope

* Real short-form video integration
* Larger Reel datasets
* User profiles and history
* Continuous personalization
* Recommendation feedback loop
* Production deployment

## Project Goal

The goal of InsightFeed is not to stop social media usage, but to make existing scrolling **more relevant, educational, and career-oriented**.
