---
title: "TON Learn: learning Web3 inside Telegram"
name: "TON Learn"
kind: concept
order: 6
state: concept
work: "Telegram Mini App that teaches Web3 basics"
period: "2025"
scale: "Concept"
role: "Idea, research, UX and UI"
lede: "A self-initiated concept: a Telegram Mini App that teaches people the basics of TON before they lose money to a phishing link."
cover: "/assets/img/ton-learn/cover.webp"
cover_alt: "TON Learn screens: home with courses in progress, a topic page and a lesson"
facts:
  Type: "Personal concept"
  Year: "2025"
  My role: "Idea, research, UX and UI"
  Platform: "Telegram Mini App"
outcomes:
  - "I presented the concept and a pitch to the community. It hasn’t shipped."
---

## Context

The idea came to me at the TON Society Balkans kick-off in Belgrade in January 2025. People new to TON kept asking the same questions, and many had already run into phishing bots.

## Problem

What people need to know about TON is spread across chats and docs, and newcomers find out about wallet security too late. Asking them to install one more app would put up another barrier.

## What I did

- **Format.** Chose a Telegram Mini App, so there is nothing extra to install.
- **Content.** Broke smart contracts, wallets and jettons into short lessons with quizzes.
- **Motivation.** Designed TON Society badges as the reward for finished courses.
- **UI.** Based the interface on Telegram Wallet, so the mini app looks like part of Telegram.

## How it works

![Home: the course in progress comes first]({{ '/assets/img/ton-learn/main.webp' | relative_url }}) ![Topic page: authors, overall progress and the fixed lesson order]({{ '/assets/img/ton-learn/theme.webp' | relative_url }}) ![Lesson: video, lecture notes, then the test]({{ '/assets/img/ton-learn/lesson.webp' | relative_url }})

- **Home.** The course a person has started stays at the top, with its progress and a Continue link. Search finds a topic, a chapter or an author. The avatar opens the profile with progress, settings and badges. A short onboarding asks what the person is into, say development, DeFi or memecoins, and the list follows that choice.
- **Topic page.** Shows the authors, so people can find material by speaker, and the progress through the topic. The lesson order never changes, so people always know what comes next. Each lesson shows how many steps are done, how long it takes and how others reacted to it.
- **Lesson page.** A lesson has 3 steps: a video in Telegram’s own player, lecture notes and a knowledge test. The test opens only after the person has gone through the materials. The badge comes when every lesson test and the final test of the topic are passed.

## Next steps

First an MVP with the core courses and a basic knowledge base. Then badges together with TON Society, and more courses after that.
