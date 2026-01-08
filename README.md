# Masai_IIT_ROPAR_Project
🎭 Emotional Storyteller

Emotion-Aware AI Story Generation System

📌 Project Overview

Emotional Storyteller is an AI-driven storytelling system that generates narratives based on human emotions, mood, and psychological context rather than rigid branching choices.
Unlike traditional decision-tree storytellers, this system adapts the story flow using emotional states, allowing narratives to feel more natural, empathetic, and immersive.

The project explores how emotional intelligence can guide narrative progression, making AI storytelling feel closer to human expression.

🎯 Problem Statement

Conventional AI storytellers rely on explicit user choices (e.g., “Go left or right”), which limits emotional depth.
Human storytelling, however, evolves through feelings, silence, hesitation, warmth, fear, and longing.

Goal:
To design a system that:

Understands emotional input

Maps emotions to narrative intent

Generates emotionally coherent story segments

💡 Key Features

Emotion-driven narrative flow

Context-aware story generation

Smooth emotional transitions (no hard branches)

Adaptive storytelling based on user’s inner state

Modular design for future LLM integration

🧠 System Design

Input

Emotional state (e.g., calm, anxious, hopeful, conflicted)

Optional contextual cues

Processing

Emotion → Narrative Intent Mapping

Emotional continuity validation

Story segment generation

Output

Emotionally aligned story scene

Tone-consistent narration

🏗️ Architecture Overview
User Emotion Input
        ↓
Emotion Mapping Layer
        ↓
Narrative Logic Engine
        ↓
Story Generation Module
        ↓
Emotionally Coherent Output

📂 Project Structure
emotional-storyteller/
│── emotional_storyteller.ipynb
│── story_engine.py
│── emotion_mapping.py
│── outputs/
│── README.md

🛠️ Technologies Used

Python

Jupyter Notebook

Rule-based emotional logic

Prompt-driven narrative generation

(Optional) LLM integration

📊 Results

Stories feel less mechanical and more reflective

Emotional continuity maintained across scenes

Improved immersion compared to choice-based storytelling

High adaptability to subtle emotional changes

| Aspect              | Observation |
| ------------------- | ----------- |
| Emotional Alignment | Strong      |
| Narrative Coherence | High        |
| Adaptability        | High        |
| Repetition          | Minimal     |
| Emotional Drift     | Controlled  |

📘 Key Learnings

Emotion is a stronger narrative driver than explicit choice

Story flow improves when emotional transitions are respected

Rule-guided emotion mapping enhances LLM outputs

Subtle emotional cues matter more than explicit commands

🚀 Future Improvements

Real-time emotion detection (text sentiment / voice)

Multi-emotion blending

Memory-aware emotional arcs

Fine-tuned LLM for emotional prose

Visual storytelling integration

📎 How to Run

Clone the repository

git clone https://github.com/your-username/emotional-storyteller.git


Open the notebook

jupyter notebook emotional_storyteller.ipynb


Run cells sequentially and provide emotional inputs

🤍 Author

Dhawal Tandon
Exploring emotion, intelligence, and narrative depth through AI.
