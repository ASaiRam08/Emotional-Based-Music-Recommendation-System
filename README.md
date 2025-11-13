# Emotional-Based-Music-Recommendation-System
# Project summary
An Emotional-Based Music Recommendation System captures users’ current emotions (or infers them), stores song metadata and emotional tags (moods), logs listening history, and produces personalized song recommendations oriented around the user’s emotional state. The DB supports content-based matching (song mood & acoustic features) and popularity signals for ranking.

# Goals
Store users, songs, moods, song acoustic features, and listening events.
Allow logging of user-reported emotion (or inferred emotion).
Provide fast recommendations tuned to current emotion using SQL (no ML required).
Support analytics: trending by mood, per-user history, top songs per emotion.

# Problem Statement
Traditional music players and streaming platforms often rely on fixed genres or popularity-based sorting, lacking emotional context. Users may struggle to find music that matches their current mood or mental state. This project solves that by creating a system that understands emotional cues and recommends songs based on mood and listening patterns.

# Objectives
Build a SQL-driven music recommendation database
Store user emotions, moods, and song metadata
Develop queries to generate emotion-based music suggestions
Track user listening behavior
Improve recommendation accuracy using acoustic features and mood tags

# Sample Data
Song records
Mood tags
Genre and mood relations
Sample listening history
