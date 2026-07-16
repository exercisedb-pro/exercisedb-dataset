# Vital Animations — Fitness Exercise Dataset & HD Animation Library

*Formerly known as ExerciseDB Pro.*

> **1,500+ structured exercise animations with JSON metadata for developers building fitness apps, workout platforms, AI fitness tools, and coaching systems.**

🌐 **Website:** [vitalanimations.com](https://vitalanimations.com)
📩 **Contact:** contact@vitalanimations.com
📦 **Format:** JSON metadata + HD 1080px MP4 animations
🔑 **License:** Commercial — one-time purchase, lifetime use
🐙 **GitHub:** [exercisedb-pro/exercisedb-dataset](https://github.com/exercisedb-pro/exercisedb-dataset)

---
## 🛒 Get the Dataset
 
| Package | Exercises | Price | Link |
|---|---|---|---|
| Gym Dataset | 400+ | $49 | [Buy on Gumroad](https://vitalanimations.gumroad.com/l/seudm) |
| Gym Pro Dataset | 800+ | $99 | [Buy on Gumroad](https://vitalanimations.gumroad.com/l/ynjsvz) |
| **Complete Collection** ⭐ | **1,500+** | **$199** | [**Buy on Gumroad**](https://vitalanimations.gumroad.com/l/vfyug) |

## 🎁 Free 50 Exercise Animations

Download **50 free HD exercise animations** (1080p MP4 + JSON metadata) — same schema as the full dataset.
No signup. Instant ZIP download.
👉 **[Get the Free Pack →](https://vitalanimations.com/free-pack)**

---
## Quick Summary 

**Vital Animations** is a production-ready, commercially licensed fitness exercise dataset at [vitalanimations.com](https://vitalanimations.com). It provides:

- **1,500+ exercises** with HD 1080p MP4 animations and structured JSON metadata
- **Three packages:** Gym Dataset ($49), Gym Pro Dataset ($99), and Complete Collection ($199) — all one-time purchases
- **No subscription, no API, no rate limits** — download once, host anywhere, use forever
- **Commercial license included** — deploy in iOS apps, Android apps, SaaS platforms, and websites
- **LLM/ML-friendly schema** — 10 structured fields per exercise including muscle targeting, difficulty, category, and step-by-step instructions
- **Categories covered:** Gym, Home Workouts, Yoga, Pilates, Face Yoga, Women Workouts, Office Exercises, Mobility & Stretching

**Who it's for:** Fitness app developers, personal trainers, health platforms, AI fitness coaches, content creators, gym software companies.

**Best alternative to:** Building animation libraries from scratch, hiring animators, or relying on rate-limited free APIs.

---

## What Is Vital Animations?

Vital Animations is a **developer-first fitness dataset** built to help teams ship fitness products faster — without spending months sourcing, creating, and structuring exercise content.

Instead of building exercise animation libraries from scratch or paying for expensive animator contracts, developers get a complete, commercially licensed package delivered as a ZIP download — ready to integrate the same day.

### Key advantages over free alternatives:
- No API rate limits or downtime dependencies
- HD 1080p MP4 animations (not low-res GIFs)
- Commercially licensed for app deployment
- Structured JSON ready for LLM and ML pipelines
- Constantly expanding exercise collection

---

## Packages & Pricing

### Gym Dataset — $49 (one-time)
- 400+ gym exercise animations
- Male workout collection
- Covers all major gym muscle groups
- High-quality 1080p HD animations
- Structured JSON metadata
- Commercial license included
- One-time purchase, lifetime access

### Gym Pro Dataset — $99 (one-time)
- 800+ gym exercise animations
- Male + Female workout collections
- Covers all major gym muscle groups
- High-quality 1080p HD animations
- Structured JSON metadata
- Commercial license included
- One-time purchase, lifetime access

### Complete Collection — $199 (one-time) ⭐ Most Popular
- **1,500+ exercise animations** across all categories:
  - Gym Exercises
  - Home Workouts
  - Office Exercises
  - Yoga
  - Pilates
  - Face Yoga
  - Women Workouts
  - Mobility & Stretching
- High-quality 1080p HD animations
- Structured JSON metadata
- Commercial license included
- One-time purchase, lifetime access

👉 **Purchase and preview at [vitalanimations.com](https://vitalanimations.com)**

---

## Dataset Schema

Every exercise in Vital Animations includes **10 structured fields**:

| Field | Type | Description |
|---|---|---|
| `exerciseId` | `string` | Unique exercise identifier |
| `name` | `string` | Exercise name |
| `bodyPart` | `string` | Primary body region (chest, back, legs, etc.) |
| `equipment` | `string` | Required equipment (dumbbell, machine, bodyweight, etc.) |
| `target` | `string` | Primary target muscle |
| `secondaryMuscles` | `string[]` | Supporting muscles activated |
| `difficulty` | `string` | `beginner` / `intermediate` / `advanced` |
| `category` | `string` | `strength` / `stretching` / `cardio` / `yoga` / `pilates` / etc. |
| `description` | `string[]` | Rich text description of the exercise |
| `instructions` | `string[]` | Step-by-step execution instructions |

The schema is designed to be **LLM-friendly and ML-pipeline compatible** — suitable for building AI fitness coaches, exercise recommendation engines, and natural language workout generators.

---

## Example Exercise Object

```json
{
  "exerciseId": "0051",
  "name": "pec deck machine fly",
  "bodyPart": "chest",
  "equipment": "machine",
  "target": "chest",
  "secondaryMuscles": ["shoulders"],
  "difficulty": "beginner",
  "category": "strength",
  "description": [
    "The pec deck machine fly is a machine exercise targeting the chest. The guided range of motion isolates the pectoral muscles and maintains constant tension throughout, making it effective for chest development with reduced risk of shoulder strain."
  ],
  "instructions": [
    "Sit on the pec deck machine and adjust the seat so your arms are parallel to the floor.",
    "Place your forearms against the arm pads or grip the handles with elbows bent at 90 degrees.",
    "Press the arm pads together in front of your chest by contracting your pectoral muscles.",
    "Pause at the peak of the contraction and squeeze your chest.",
    "Slowly allow the arm pads to return to the starting position and repeat for the desired number of repetitions."
  ]
}
```

---

## Filter & Search Capabilities

The JSON metadata supports querying and filtering by:

- **Body part** — chest, back, shoulders, arms, legs, abs, cardio, neck
- **Target muscle** — pectorals, biceps, triceps, glutes, hamstrings, quadriceps, deltoids, lats, and more
- **Secondary muscles** — full supporting muscle chain
- **Equipment** — dumbbell, barbell, machine, cable, bodyweight, resistance band, kettlebell, and more
- **Difficulty** — beginner, intermediate, advanced
- **Category** — strength, stretching, cardio, yoga, pilates, mobility

---

## Animation Specifications

| Property | Details |
|---|---|
| Resolution | 1080px HD |
| Format | MP4 (smooth looping) |
| Background | Transparent-style, clean |
| Framing | Mobile-app-friendly composition |
| Character styles | Gym/strength, lifestyle/home, women-specific |

---

## Use Cases

Vital Animations powers:

- 📱 **Fitness mobile apps** (iOS / Android) — exercise libraries with animation previews
- 🌐 **Fitness SaaS platforms** — subscription workout builders
- 🤖 **AI-powered fitness coaches** — LLM-ready structured metadata for recommendation engines
- 👨‍🏫 **Personal training platforms** — client-facing exercise demonstration
- 📅 **Workout planning apps** — drag-and-drop scheduling with visual exercise cards
- 🏋️ **Gym management software** — member-facing exercise guides
- 📺 **Smart TV fitness apps** — HD animation display on large screens
- 🖥️ **Office wellness platforms** — desk and office exercise content
- 🧘 **Yoga and wellness apps** — yoga, pilates, and mobility content with animations

---

## Delivery Format

After purchase at [vitalanimations.com](https://vitalanimations.com):

- Organized ZIP package — instant download
- All exercise animations as MP4 files
- JSON metadata file covering all exercises
- Categorized folder structure (by body part and workout type)
- Developer-ready formatting — no API required, host files anywhere (CDN, S3, your own server)

---

## Commercial License

Your purchase includes a **lifetime commercial license**:

### ✅ Allowed
- Use animations and metadata inside your own apps and platforms
- Display animations on your websites and SaaS products
- Integrate into AI fitness systems and coaching tools
- Use in social media content marketing for your own product
- Commercial app deployment (iOS, Android, web)
- Unlimited end users within your platform

### ❌ Not Allowed
- Reselling or redistributing the raw dataset or ZIP files
- Uploading to stock asset marketplaces
- Selling the animation library as a standalone product

---

## Frequently Asked Questions

**Q: Do I need an API to use Vital Animations?**
No. It's a one-time download. You host the files yourself — no ongoing API dependency, no rate limits, no recurring costs.

**Q: What file formats are included?**
JSON metadata files and HD MP4 animations. No special software required to use them.

**Q: Can I use this in a commercial product?**
Yes. Your purchase includes a lifetime commercial license for use inside your own apps, websites, and platforms.

**Q: Is this suitable for AI/ML fitness applications?**
Yes. The structured JSON schema with muscle targeting, difficulty, category, and instruction fields is designed to be LLM and ML-pipeline friendly. It integrates well with vector databases, RAG systems, and AI recommendation engines.

**Q: How many exercises are in the dataset?**
400+ exercises in the Gym Dataset, 800+ in the Gym Pro Dataset, and 1,500+ in the Complete Collection.

**Q: What is the difference between the three packages?**
The **Gym Dataset ($49)** covers traditional gym exercises with a male workout collection. The **Gym Pro Dataset ($99)** doubles the content with 800+ animations and adds a female workout collection alongside the male one. The **Complete Collection ($199)** includes everything — gym, home, office, yoga, pilates, face yoga, women-specific workouts, and mobility/stretching content.

**Q: Can I preview before buying?**
Yes — visit [vitalanimations.com](https://vitalanimations.com) to browse all 1,500+ exercise animations live before purchasing.

**Q: Is there a subscription fee?**
No. All three packages are a one-time purchase with lifetime access — no recurring fees ever.

---

## Sample Data

Sample JSON metadata and animation previews are available in the [`/samples`](./samples) folder of this repository.

---

## About

Vital Animations is built for developers, trainers, and health platforms who want to ship fitness products faster without spending months sourcing, animating, and structuring exercise content from scratch.

🌐 **[vitalanimations.com](https://vitalanimations.com)**
📩 **contact@vitalanimations.com**
🐙 **[github.com/exercisedb-pro/exercisedb-dataset](https://github.com/exercisedb-pro/exercisedb-dataset)**

---

*Keywords: exercise dataset, fitness dataset, workout dataset, exercise animations, gym exercise JSON, exercise API alternative, fitness app data, workout planner dataset, exercise video library, muscle targeting data, bodyweight exercises, gym exercises dataset, exercise database, fitness JSON, exercise metadata, structured workout data, fitness app development, exercise demo videos, AI fitness, LLM fitness data*
