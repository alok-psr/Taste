# ✨ Taste — A Personalized Content Discovery Engine

> Not another feed.  
> A system that learns *your taste* — and helps good writing get discovered.

---

## 📌 What is Taste?

**Taste** is a personalized content discovery platform designed to surface articles you’ll genuinely enjoy — not just what’s popular or loud.

It learns from **what you read, save, skip, and explicitly feed into the system**, and adapts over time to reflect your evolving interests. Beyond personalization, Taste has a clear mission:  
**to promote high-quality writing from independent creators who lack reach but deserve attention.**

---

## 🧠 Core Philosophy

Good content shouldn’t lose to algorithms optimized for virality.

Taste is built on three principles:

- **User control over opaque tracking**
- **Quality and depth over popularity metrics**
- **Discovery driven by taste, not trends**

---

## 🚀 Key Features

### 1. Personalized Reading Feed
- A continuously updating **“For You”** stream
- Ranked using explicit preferences and implicit behavior
- Filters by topic, recency, and reading length
- Explainable recommendations (why an article was shown)

---

### 2. User-Taught Recommendation Engine
Taste doesn’t guess blindly — users *teach* it.

Signals include:
- Reading time
- Likes, saves, skips
- Topics followed
- Explicit content fed by the user

Stronger signals receive higher influence, leading to faster and more accurate personalization.

---

### 3. Grammarly-Style Browser Extension
A lightweight browser extension allows users to feed content directly into their recommender.

- Floating action icon appears on text selection or article pages
- One-click **“Feed this to my recommender”**
- Works on any website
- Only explicitly selected URLs or text are sent — no background tracking

This feature solves the cold-start problem and gives users full agency.

---

### 4. Hidden Gems Discovery (Future-Focused)
Taste actively surfaces **high-quality writing from creators who lack reach**.

A dedicated section (planned) will:
- Reduce reliance on popularity signals
- Reward depth, originality, and consistency
- Promote independent blogs that resonate with user taste

If multiple users independently like the same lesser-known writer, their work gains organic visibility.

---

### 5. Personalized Newsletter
An optional, opt-in newsletter delivers curated content directly to the inbox.

- Daily or weekly cadence
- Selected using the same recommendation engine
- Mix of:
  - Highly relevant articles
  - Fresh discoveries
  - At least one “Hidden Gem”
- Transparent explanations for each inclusion

Taste comes to you — not the other way around.

---

## 🛠️ Recommendation Approach

Taste starts simple and evolves naturally.

**Initial Approach (No Heavy ML):**
- Rule-based and heuristic ranking
- Topic relevance
- Source affinity
- Freshness weighting
- Strong weighting for explicit user-fed content
- Signals favoring reading completion over clicks

**Future Upgrade (Optional):**
- Text embeddings for semantic similarity
- No custom model training required initially

---

## 🧩 Technical Overview

- Content ingestion via RSS feeds and public APIs
- Backend scoring and ranking service
- Clean, focused reading UI
- Browser extension for explicit signal injection
- Email delivery pipeline for newsletters
- Modular architecture designed for gradual ML integration

---

## 🔒 Privacy & Transparency

- No passive tracking
- No selling user data
- Only content explicitly selected by the user is analyzed
- Clear explanations for recommendations

Taste is designed to earn trust, not extract attention.

---

## 🧭 Why Taste?

Most platforms optimize for:
- clicks
- engagement loops
- virality

Taste optimizes for:
- relevance
- depth
- discovery
- genuine interest

It’s not about consuming more —  
it’s about consuming **better**.

---

## ✍️ One-Line Summary

> Taste is a personalized content discovery platform with a Grammarly-style browser extension and smart newsletter that lets users teach their recommender — while surfacing high-quality writing from creators who deserve more reach.

---

## 📬 Status

This project is under active development and designed to evolve incrementally:
- Start focused
- Ship fast
- Learn continuously

Contributions, ideas, and thoughtful discussions are always welcome.

---

*Built with curiosity, restraint, and respect for good writing.*
