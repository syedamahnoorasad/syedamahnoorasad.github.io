---
title: "UNO Multiplayer"
excerpt: "Real-time four-player UNO built with a TypeScript backend and modern React client."
collection: projects
date: 2024-01-15
permalink: /projects/uno/
banner: /images/project/uno/lobby.png
images:
  - /images/project/uno/lobby.png
  - /images/project/uno/game-play.png
  - /images/project/uno/message-panel.png
  - /images/project/uno/wild-card-choice.png
  - /images/project/uno/game-end-win.png
skills:
  - Real-time Systems
  - TypeScript
  - Node.js
  - Socket.IO
  - React
  - State Management
  - CSS Animation
role: "Full-stack Developer"
repo_url: "https://github.com/syedamahnoorasad/UNO"
---

## Overview

UNO Multiplayer is a real-time game that seats four players in a shared lobby, synchronises every card play, and broadcasts turn events instantly. The experience combines a TypeScript Socket.IO backend with a React client that renders an animated UNO table, message log, and card overlays.

<div style="margin:24px 0;">
  <a href="{{ page.repo_url }}" class="btn btn--primary" target="_blank" rel="noopener">
    View Source on GitHub
  </a>
</div>

## Gameplay Highlights

- **Instant lobby sync:** Players join a shared room, receive seating assignments, and kick off a match as soon as four participants connect.
- **Live turn messaging:** A sidebar stream announces whose turn it is, which card was played, color changes, and UNO calls for fast awareness.
- **Wild card overlay:** Color selection popups pause the table and broadcast the chosen color to every player before play resumes.
- **Win celebrations:** UNO declarations and victory banners animate the board when a player empties their hand.

## Tech Stack

- **Backend:** Node.js, Express, Socket.IO, TypeScript, ts-node.
- **Frontend:** React, TypeScript, React Router, Socket.IO Client (Create React App).
- **Styling:** Custom CSS theming of the table, cards, and message overlay.

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;">
  <figure style="margin:0;">
    <img src="/images/project/uno/lobby.png" alt="UNO lobby screen showing four seats" style="width:100%;border-radius:8px;" />
    <figcaption>Lobby seats players as they join and launches the match when all four spots fill.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/uno/game-play.png" alt="UNO gameplay with four players around the table" style="width:100%;border-radius:8px;" />
    <figcaption>Game table displays every player's hand count, active color, and discard pile in real time.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/uno/message-panel.png" alt="Live message panel announcing turn updates" style="width:100%;border-radius:8px;" />
    <figcaption>Animated message panel delivers turn prompts, draw notices, and UNO shouts.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/uno/wild-card-choice.png" alt="Wild card color selection overlay" style="width:100%;border-radius:8px;" />
    <figcaption>Wild card overlay lets the current player pick the next color with instant broadcast to all.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/uno/game-end-win.png" alt="UNO win screen showing banner and confetti" style="width:100%;border-radius:8px;" />
    <figcaption>Victory screen highlights the winning player with banner and confetti animation.</figcaption>
  </figure>
</div>
