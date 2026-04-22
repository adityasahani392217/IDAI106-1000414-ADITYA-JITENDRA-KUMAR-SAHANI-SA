# Ideation & Conceptualization
## CareEase Hospital Queue App | Design Thinking — Ideate Stage

---

## Brainstorming Approach

The team used a "Crazy 8s" brainstorming method on Miro — generating 8 rough ideas in 8 minutes each, then expanding the best ones. Ideas were grouped into categories and evaluated using a 2x2 Priority Matrix (High/Low Impact vs High/Low Effort).

---

## Raw Idea Bank (25+ ideas generated)

| # | Idea | Category |
|---|------|----------|
| 1 | Live queue position on home screen | Queue Tracking |
| 2 | Estimated time shown as a range (e.g. "10–20 min") | Queue Tracking |
| 3 | Countdown timer for last 10 minutes | Queue Tracking |
| 4 | Vibration alert when 3 patients ahead | Silent Alerts |
| 5 | Sound + light flash notification for hearing-impaired | Accessibility |
| 6 | Companion app link — caregiver gets same alerts | Caregiver Support |
| 7 | Calming nature sounds playlist | Distraction |
| 8 | Guided breathing exercise with animation | Mood/Mindfulness |
| 9 | VR forest walk on phone screen | Distraction (AR/VR) |
| 10 | 360-degree calming room simulation | Distraction (AR/VR) |
| 11 | Kids cartoon zone — age-appropriate animations | Kids Zone |
| 12 | Interactive colouring for children | Kids Zone |
| 13 | "What to expect" walkthrough for first-timers | Onboarding |
| 14 | Mood check-in slider (1–5) with empathy response | Mood Tracking |
| 15 | Personalised message based on mood score | Emotional Support |
| 16 | Feedback form at end of visit | Feedback |
| 17 | Stress level rating before and after wait | Feedback |
| 18 | Anonymous suggestions box | Feedback |
| 19 | Hindi/English language toggle | Accessibility |
| 20 | Large text mode for elderly | Accessibility |
| 21 | Screen reader support | Accessibility |
| 22 | Hospital map showing which floor/room to go | Navigation |
| 23 | Doctor profile — "who you will see today" | Information |
| 24 | Health tips carousel while waiting | Wellness Content |
| 25 | Post-visit appointment booking | Extended Feature |
| 26 | Offline mode for poor hospital Wi-Fi | Technical |
| 27 | Low-battery mode that strips UI to essentials | Technical |

---

## Priority Matrix

```
HIGH IMPACT
     │
     │  [Queue Tracker]    [Silent Alerts]
     │  [Mood Interaction]  [Distraction Hub]
     │  [Accessibility]     [Kids Zone]
     │
     │  [Guided Breathing]  [Companion Link]
     │
─────┼──────────────────────────────────────────
LOW  │  [VR Forest Walk]   [Hospital Map]
EFFORT│ [Health Tips]      [Doctor Profile]
     │
     │
     LOW IMPACT
```

---

## 5 Compulsory Features — Detailed Specification

### Feature 1: Queue Progress Tracker
**What it does:** Displays the patient's real-time position in the queue, estimated wait time range, and a visual progress bar.

**How it works:**
- On registration, patient receives a token number
- App fetches live queue data from hospital system
- Shows: "You are #7 in queue | Approx. 18–25 minutes remaining"
- Progress bar fills as queue moves
- Refreshes automatically every 60 seconds
- Shows a "Queue has slowed" message if delays occur

**Design notes:** Teal colour scheme (calming). Large, readable font. Accessible in Hindi and English.

---

### Feature 2: Distraction Hub
**What it does:** A curated content space offering calming videos, nature sounds, mindfulness exercises, short reads, and a dedicated Kids Zone.

**Sections:**
- Calm Sounds: nature audio (rain, forest, ocean)
- Short Videos: feel-good, non-medical 2–5 minute clips
- Kids Zone: cartoons, interactive colouring, simple games (age 2–10)
- Mindfulness Corner: breathing exercises, body scan audio
- Health Tips: carousel of simple wellness facts

**Design notes:** Icon-based navigation for low-literacy users. Hindi/English toggle. Kids Zone uses bright colours separately from the calm adult palette.

---

### Feature 3: Silent Pager Notifications
**What it does:** Sends phone vibration + silent push notification when patient is 3 turns away, 1 turn away, and when it is their turn.

**Notification sequence:**
- "3 more patients ahead — please stay nearby" (vibration)
- "Next! Please make your way to the counter" (vibration + banner)
- Companion phone receives same alerts if linked

**Design notes:** Works on silent mode. Visual flash option for deaf users. Large banner text. No loud sound — patient can stay in Distraction Hub without fear.

---

### Feature 4: Mood-Based Interactions
**What it does:** At check-in, patient rates their mood on a 5-point scale. App responds with personalised messages and appropriate content.

**Mood levels and responses:**

| Mood Score | Label | App Response |
|------------|-------|-------------|
| 1 | Very Calm | "Great — enjoy the Distraction Hub" |
| 2 | Okay | "Here are some calming suggestions for you" |
| 3 | Slightly Anxious | Breathing exercise prompt + empathy message |
| 4 | Anxious | Guided breathing exercise auto-starts + "You are in safe hands" message |
| 5 | Very Stressed | Breathing + empathy message + option to request staff support |

**Content served based on mood:** Music tempo, video type, and message tone all adjust automatically.

---

### Feature 5: Feedback Section
**What it does:** At the end of the visit, patients rate their waiting experience and provide suggestions.

**Fields:**
- Stress level before wait (1–5)
- Stress level after using the app (1–5)
- Which features helped most (multi-select)
- Open text suggestion
- Overall experience star rating (1–5)
- Optional: name and contact for follow-up

**Data use:** Responses feed into hospital's CareEase dashboard for monthly experience review.

---

## 3 Bonus / Innovative Features

### Bonus Feature 1: Companion Link
The patient can share a "Companion Code" with a family member outside the hospital. The companion's phone receives the same queue alerts — so they know when to come back inside. Designed specifically for Ishant's situation (elderly patient with caregiver).

### Bonus Feature 2: Multilingual Interface
Full support for Hindi and English with a one-tap toggle on every screen. All queue information, mood messages, and notifications appear in the selected language. Designed for Gudiya Sahani, Priya Mehta, and Lalita Devi personas.

### Bonus Feature 3: Accessibility Mode
One-tap activation of: large text (24px minimum), high contrast, screen reader compatibility, and vibration-only alerts. Designed for elderly users and hearing/vision-impaired patients.

---

## Tools Used for Ideation

| Tool | Purpose |
|------|---------|
| Miro | Collaborative sticky note brainstorming, priority matrix |
| MindMeister | Mind map of feature categories |
| Figma FigJam | Quick sketches and user flow diagrams |
| Google Sheets | Feature prioritisation scoring |
