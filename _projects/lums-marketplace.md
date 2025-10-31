---
title: "LUMS Marketplace"
excerpt: "Campus-only web marketplace helping LUMS students trade pre-loved items safely with verified access."
collection: projects
date: 2023-12-02
permalink: /projects/lums-marketplace/
banner: /images/project/lumsmarketplace/home.png
images:
  - /images/project/lumsmarketplace/home.png
  - /images/project/lumsmarketplace/listing.png
  - /images/project/lumsmarketplace/product-detail.png
  - /images/project/lumsmarketplace/favorites.png
  - /images/project/lumsmarketplace/mobile.png
  - /images/project/lumsmarketplace/chat.png
  - /images/project/lumsmarketplace/dashboard.png
  - /images/project/lumsmarketplace/moderation.png
skills:
  - Requirements Engineering
  - Full-Stack Development
  - React
  - Node.js
  - MongoDB
  - JavaScript
  - TypeScript
  - Surveys
role: "Full-stack Developer & Requirements Lead"
video_demo: "https://drive.google.com/file/d/1VBFIQqfnSQzzEV0P-TS8tMPyZxADenDc/view?usp=sharing"
---

## Overview

LUMS Marketplace is a five-person group project that provides a verified, campus-only space for students to buy, sell, and donate second-hand items. We set out to replace ad-hoc resale chats with a structured platform that keeps transactions transparent and easy to manage.

<div style="margin:24px 0;">
  <a href="{{ page.video_demo }}" class="btn btn--primary" target="_blank" rel="noopener">
    Watch the Product Walkthrough
  </a>
</div>

## Motivation

- **Fragmented resale channels:** Listings disappeared inside temporary WhatsApp groups, making it difficult to track items or compare offers.
- **Trust and safety:** Students wanted identity checks, moderation, and report workflows before committing to in-person exchanges.
- **Sustainable reuse:** A central marketplace extends the life of course materials, electronics, and dorm essentials while keeping costs low for newcomers.

## My Role

- Collaborated within a five-member team to align requirements, sprint goals, and testing feedback.
- Co-authored the requirements specification, translating survey findings into use cases and acceptance criteria for the team.
- Built core React + TypeScript interfaces including the filtered listing view, saved items page, and responsive layout tweaks.
- Implemented and tested Express/MongoDB endpoints for listings, messaging, and moderation so buyer-seller flows stayed reliable.

## Platform Capabilities

- **Student experience:** LUMS email sign-up, profile management, saved searches, and in-platform messaging that keeps conversations attached to each listing.
- **Seller toolkit:** Multi-image postings, price edits, status toggles (available, sold), and a quick snapshot of active inventory.
- **Search & discovery:** Keyword filters, category chips, and sort controls that help students find the exact textbooks or gear they need.
- **Moderation & support:** Reporting tools and admin dashboards that surface flagged content for review and keep the community accountable.

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;">
  <figure style="margin:0;">
    <img src="/images/project/lumsmarketplace/home.png" alt="LUMS Marketplace home dashboard" style="width:100%;border-radius:8px;" />
    <figcaption>Home feed highlights fresh listings, active chats, and quick actions for sellers.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/lumsmarketplace/listing.png" alt="Listings page with filters expanded" style="width:100%;border-radius:8px;" />
    <figcaption>Listing detail view keeps specs, price, and buyer/seller actions in one panel.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/lumsmarketplace/product-detail.png" alt="Product detail page with reviews and messaging call-to-action" style="width:100%;border-radius:8px;" />
    <figcaption>Review submission flow lets buyers add feedback after successful trades.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/lumsmarketplace/favorites.png" alt="Saved items gallery" style="width:100%;border-radius:8px;" />
    <figcaption>Review history consolidates all published feedback for transparency.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/lumsmarketplace/mobile.png" alt="Mobile responsive view of marketplace" style="width:100%;border-radius:8px;" />
    <figcaption>User profile highlights listings, ratings, and contact options.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/lumsmarketplace/chat.png" alt="Messaging interface between buyer and seller" style="width:100%;border-radius:8px;" />
    <figcaption>Filter panel exposes category, location, and price range controls.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/lumsmarketplace/dashboard.png" alt="Seller dashboard with metrics and quick actions" style="width:100%;border-radius:8px;" />
    <figcaption>Admin view lists all users with controls for verification and flags.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/project/lumsmarketplace/moderation.png" alt="Admin moderation panel" style="width:100%;border-radius:8px;" />
    <figcaption>Additional filter options include setting minimum and maximum price.</figcaption>
  </figure>
</div>

## Tech Stack

- **Frontend:** React with TypeScript for modular UI components and stateful filters.
- **Backend:** Node.js + Express services powering listings, messaging, and moderation APIs.
- **Database:** MongoDB storing users, inventory, chat threads, and moderation logs.
