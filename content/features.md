---
title: "Glosso Studio"
date: 2026-03-24T00:00:00Z
draft: false
---

Glosso Studio is an **offline-first** pronunciation training app that helps you master spoken English with phoneme-level feedback.

<p class="lead">Powered by Allosaurus and ONNX Runtime — no internet connection required.</p>

---

## How it works

Unlike traditional language apps that rely on simple speech-to-text, **Glosso** analyzes the phonetic components of your speech for granular, actionable feedback.

### Phonetic Assessment

Real-time recognition using the **Allosaurus** model processes 8kHz audio and provides detailed feedback on pronunciation accuracy down to the individual phoneme.

### Offline-first

Fully functional without an internet connection. Acoustic models and curriculum databases run directly on your device via **ONNX Runtime**.

### Progressive Curriculum

Six difficulty tiers ranging from Beginner to Mastery. Structured learning paths help you build confidence and skill over time.

### Mastery System

Achieve threshold scores (85%+) to master sentences. Track your consistency with a daily streak system and detailed statistics.

### High-Fidelity TTS

Integrated with **Qwen3-TTS** for natural-sounding speech synthesis, allowing you to hear perfect pronunciation before you practice.

### Real-time Statistics

Visualize your progress with comprehensive tracking of total mastered phrases and level-specific advancement metrics.

---

## Download

<a class="btn btn-pri" href="https://gitlab.com/shirobyte421/glosso-studio/-/releases" target="_blank">GitLab Releases</a>

Build from source:

```bash
git clone git@gitlab.com:shirobyte421/glosso-studio.git
cd glosso-studio
git lfs install && git lfs pull
```
