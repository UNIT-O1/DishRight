<div align="center">

# DishRight

### Redefining Cooking.

[![Status](https://img.shields.io/badge/status-in%20development-orange?style=for-the-badge)](#)
[![Platform](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue?style=for-the-badge)](#)
[![Design](https://img.shields.io/badge/design-figma-9146FF?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/proto/UdwD5CQNMKN4btfXaA9ty9/DishRight?node-id=0-1&t=xXfseXsYgtSDbErl-1)
[![License](https://img.shields.io/badge/license-proprietary-lightgrey?style=for-the-badge)](#)

</div>

<br>

> [!TIP]
> ### Prototype & Pitch
> **[View the Project Pitch (PDF)](./DishRight.pdf)** &nbsp;&middot;&nbsp; **[Open the Figma Prototype](https://www.figma.com/proto/UdwD5CQNMKN4btfXaA9ty9/DishRight?node-id=0-1&t=xXfseXsYgtSDbErl-1)**
>
> The PDF covers the full pitch deck — problem, solution, market sizing, competitive landscape, revenue model, and go-to-market strategy. The Figma link is a clickable, interactive walkthrough of the actual product experience.

<br>

<div align="center">

| [Overview](#overview) | [The Problem](#the-problem) | [Our Solution](#our-solution) | [Features](#features) | [Product Flow](#product-flow) | [Tech Stack](#tech-stack) | [Market Opportunity](#market-opportunity) | [Business Model](#business-model) | [Competitive Advantage](#competitive-advantage) | [Go-To-Market](#go-to-market-strategy) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|

</div>

<br>

## Overview

**DishRight** is a cooking platform designed to make recipe discovery and preparation easier by adapting recipes to the user's needs.

It addresses common problems such as adjusting ingredient quantities, deciding what to cook, and finding recipes based on available time, ingredients, and preferences — turning a tedious, error-prone process into a guided, personalized experience.

<br>

## The Problem

Cooking often involves a series of small, repetitive frictions that add up over time:

<table>
<tr>
<td width="50%" valign="top">

**Quantity & Proportion**
- Fixed-portion recipes don't scale to the number of people being served
- Estimating proportions when ingredients are limited leads to imbalanced flavor
- Manual adjustments are time-consuming and often inaccurate

</td>
<td width="50%" valign="top">

**Decision & Discovery**
- Deciding what to cook is a daily source of friction
- Finding dishes based on available time or ingredients is hard
- Recipe sources show *process*, not the *proportions* needed for a specific taste
- Home cooks with a passion for sharing recipes lack an easy outlet to do so

</td>
</tr>
</table>

> Unless a cook is highly experienced, incorrect proportions lead to inconsistent results, wasted ingredients, and unnecessary expense — and the overall journey from "I want to cook" to "I'm actually cooking" is simply tedious.

<br>

## Our Solution

> [!NOTE]
> **We solve those problems.**
>
> | Capability | What it does |
> |---|---|
> | **Auto-Scales Recipes** | Adjusts proportions automatically based on servings or available ingredients |
> | **Prevents Food Waste** | Exact measurements mean no unnecessary leftovers |
> | **Ensures Perfect Taste** | Maintains the correct flavor balance at any scale |
> | **Simplifies Cooking** | Removes manual calculation from the cooking process entirely |
> | **Saves Money** | Users buy and use only what a recipe actually requires |

<br>

## Features

<table>
<tr>
<td width="33%" valign="top">

### Recipe Scaling
Adjust ingredient quantities automatically based on the required number of servings — while preserving flavor balance.

</td>
<td width="33%" valign="top">

### Dish Recommendations
Personalized dish suggestions ("Handpicked delights") generated from user data and preferences.

</td>
<td width="33%" valign="top">

### Xplore
An extensive filtered search to decide what to cook, based on:
- Available time — *Quick Bites (~15 min), Standard (~30 min), Slow-Delight (30+ min)*
- Ease of cooking
- Vegetarian / Non-vegetarian
- Region

</td>
</tr>
<tr>
<td width="33%" valign="top">

### Lens
Point the camera at a dish to instantly identify it and retrieve its name, ingredients, and recipe.

</td>
<td width="33%" valign="top">

### Community
A social feed where users share their own recipes, with **Latest** and **Top** feeds for discovery and engagement.

</td>
<td width="33%" valign="top">

### Smart Checkout
When ingredients are missing, users can order them directly via **Swiggy Instamart**, **BigBasket**, or **Blinkit** without leaving the app.

</td>
</tr>
</table>

<br>

## Product Flow

<div align="center">

```
  Want to cook
       │
       ▼
Discover / Search  ──▶  Xplore, Lens, Community, or Recommendations
       │
       ▼
  Choose a dish
       │
       ▼
  Get the recipe    ──▶  Prep time, cook time, difficulty, ingredient checklist
       │
       ▼
 Adapt proportions  ──▶  Auto-scaled by quantity & spice preference
       │
       ▼
Order missing items ──▶  via Swiggy Instamart / BigBasket / Blinkit (optional)
       │
       ▼
      Cook
```

</div>

<br>

## Tech Stack

> [!IMPORTANT]
> ### Planned Technology Stack
>
> | Layer | Technology | Purpose |
> |---|---|---|
> | **Mobile App** | `React Native` | Cross-platform app for Android & iOS from a single codebase |
> | **UI / UX Design** | `Figma` | Interface design and interactive prototyping |
> | **AI / ML** | `TensorFlow` &nbsp;/&nbsp; `PyTorch` | Recipe proportion scaling and image-based dish recognition (Lens) |
> | **Cloud & Storage** | `AWS` &nbsp;/&nbsp; `Google Cloud` | App data, user interactions, and media storage |
> | **Third-Party Integrations** | `Swiggy Instamart` &middot; `BigBasket` &middot; `Blinkit` | In-app ingredient ordering |

<br>

## Market Opportunity

<table>
<tr>
<td width="50%" valign="top">

### India

- Indian food-tech market size: **$79B** (2023), growing at **10.2% CAGR**
- **80%+** of Indian households cook at home daily
- **500M+** smartphone users with rising internet penetration, driving food-content consumption
- Post-pandemic shift toward health-conscious, home-cooked meals

**Target audience**
- Home Cooks — precise portions for family meals
- Students & Bachelors — budget-friendly, no-waste meal prep
- Cooking Hobbyists — precision to sharpen skills
- Health-Conscious Users — diet-based recipes & meal plans

</td>
<td width="50%" valign="top">

### Global

- Global recipe app market size: **$724.4M** (2024)
- Projected to reach **$2,268M by 2033** at a **13.5% CAGR**
- Regional share: **North America 35.7%** ($238.2M) &middot; **Europe 31.2%** &middot; **Asia-Pacific 26.3%**
- Reference competitor: **CookPad** (Japan) — ~100M monthly users, ad-driven, trailing 12-month revenue of **$38.8M** (as of Dec 2024)

</td>
</tr>
</table>

<br>

## Business Model

**Revenue paths**

| Stream | Description |
|---|---|
| Advertisements & Sponsorships | Food brands, spice companies, kitchen appliance brands |
| B2B Partnerships / Data Monetization | Integration with Swiggy, Zomato, BigBasket, Blinkit for smart ingredient recommendations and purchase commissions |
| Freemium Model *(under evaluation for India)* | Free basic proportion scaling; premium tier for advanced meal planning & personalized diet tracking |
| In-App Purchases *(under evaluation for India)* | Exclusive Indian recipe packs and regional meal plans |

<br>

## Competitive Advantage

- No major competitor currently offers **AI-based recipe proportion scaling**
- Designed around **regional dishes**, unlike global-first incumbents such as CookPad
- **Community feature** — users share and discover recipes, unlike static, one-directional recipe apps
- **AI-driven suggestions** based on available ingredients, time constraints, and preferences (veg/non-veg, regional cuisine, dietary needs)
- **Lens** — identify a dish from a photo and instantly retrieve its recipe, ingredients, and steps
- CookPad, by comparison, is limited to being a recipe-sharing app with no proportion intelligence

<br>

## Go-To-Market Strategy

<table>
<tr>
<td width="25%" valign="top">

**Pre-Launch**
- Market research
- Product development
- Beta testing with students, college groups, and food enthusiasts

</td>
<td width="25%" valign="top">

**Launch**
- Soft launch in India, top metro cities first (high digital adoption)
- User acquisition via digital marketing & paid ads
- Retention via personalization and community

</td>
<td width="25%" valign="top">

**Growth**
- Sponsorship pitches based on active user base
- Partnerships with Swiggy, Zomato, BigBasket, Blinkit
- Expanded social media marketing
- Sponsored physical recipe contests

</td>
<td width="25%" valign="top">

**Scaling**
- Expansion to other Tier-1 cities
- Later expansion to Tier-2 cities

</td>
</tr>
</table>

<br>

---

<div align="center">

**DishRight** &middot; Built to make cooking simpler, one recipe at a time.

</div>
