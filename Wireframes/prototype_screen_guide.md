# Prototype Screen Guide — CareEase App
## Design Thinking | Prototype Stage
**Tool Used:** Figma  
**Prototype Type:** Clickable, mobile-first (Android/iOS compatible)  
**Screens Designed:** 12 screens with interactive flows

---

## Design System

| Element | Value |
|---------|-------|
| Primary Color | Teal — #1D9E75 (calming, health-associated) |
| Secondary Color | Light Green — #E1F5EE (backgrounds, cards) |
| Warning/Alert Color | Amber — #EF9F27 |
| Text Primary | Dark Gray — #2C2C2A |
| Text Secondary | Medium Gray — #888780 |
| Font | Inter (clean, accessible, multilingual) |
| Border Radius | 12px (rounded, friendly) |
| Min Font Size | 16px (accessibility-first) |

---

## Screen 1: Splash / Onboarding
**Purpose:** First impression. Sets calm, trustworthy tone.  
**Elements:**
- CareEase logo (teal leaf + cross icon)
- Tagline: "Your wait, made calmer."
- Language selection: English / हिंदी
- Accessibility prompt: "Do you need larger text?" → Yes / No
- "Get Started" button

---

## Screen 2: Patient Registration / Token Entry
**Purpose:** Link patient to queue system.  
**Elements:**
- Input field: "Enter your token number"
- OR "Scan QR code from your hospital slip"
- Name display: "Welcome, Jitendra"
- Companion Link shortcut: "Share alerts with a family member"
- Continue button → leads to Home/Dashboard

---

## Screen 3: Home Dashboard (Queue Tracker — Feature 1)
**Purpose:** Core screen. Real-time queue position. Main hub.  
**Elements:**
- Top bar: CareEase logo + Accessibility toggle + Language toggle
- Patient name and token: "Jitendra Sahani — Token #A047"
- Queue card (teal):
  - "Your position: #7 in queue"
  - Progress bar (7/25 filled)
  - Estimated wait: "18–25 minutes"
  - Last updated: "2 min ago"
  - Department: "Outpatient — Diabetes"
- Mood Check-in prompt card: "How are you feeling? 😌 → 😰"
- Quick links row: Relax & Explore | Breathe | Companion | Feedback
- Notification bell icon (top right)

---

## Screen 4: Silent Pager / Notification Screen (Feature 3)
**Purpose:** Show what the silent alert looks like when turn is approaching.  
**Elements:**
- Full-screen teal banner: "Your turn is coming!"
- Sub-text: "2 patients ahead — please make your way to the counter"
- Large token number: #A047
- Countdown indicator: "Approx. 4 minutes"
- "I'm on my way" confirmation button (green)
- Vibration icon shown in corner to indicate silent mode active
- Companion notification preview: "Ishant's phone also received this alert"

---

## Screen 5: Mood Check-In (Feature 4 — Part A)
**Purpose:** Let patient rate current emotional state.  
**Elements:**
- Title: "How are you feeling right now?"
- 5-point emoji slider:  
  😌 Very Calm → 🙂 Okay → 😐 Bit Anxious → 😟 Anxious → 😰 Very Stressed
- Each emoji labeled in selected language
- "Continue" button → leads to personalised response screen

---

## Screen 6: Mood Response Screen (Feature 4 — Part B)
**Purpose:** Deliver empathy message and content based on mood score.  
**Elements (example for score 4 — Anxious):**
- Warm message: "It's okay to feel anxious. You are in safe hands today."
- Suggested action card: "Try a 2-minute breathing exercise"
- Teal leaf illustration (calming visual)
- Quick buttons: "Start Breathing" | "Play Calming Sounds" | "Back to Queue"
- Auto-suggested content queued in Distraction Hub

---

## Screen 7: Relax & Explore — Distraction Hub (Feature 2)
**Purpose:** Content hub to pass time and reduce stress.  
**Sections (scrollable card grid):**
- Calm Sounds (rain, forest, ocean — tap to play)
- Kids Zone (bright, separate palette — cartoons, colouring)
- Short Videos (feel-good 2–3 min clips)
- Mindfulness Corner (guided audio exercises)
- Trending (short video content for younger users)
- Health Tips (swipeable cards)
**Header:** Background audio now playing: [Forest Rain] — tap to change

---

## Screen 8: Guided Breathing Screen (Feature 2 — Mindfulness)
**Purpose:** Interactive breathing animation for anxiety relief.  
**Elements:**
- Animated expanding/contracting circle (inhale 4s / hold 2s / exhale 6s)
- Text: "Breathe in... Hold... Breathe out..."
- Background: soft gradient (teal to white — exception allowed for animation)
- Session timer: "2:30 remaining"
- Background audio: low ambient sound
- "I feel better" button → returns to Dashboard with updated mood logged

---

## Screen 9: Kids Zone (Distraction Hub sub-screen)
**Purpose:** Age-appropriate content for children 2–10.  
**Elements:**
- Bright yellow/orange palette (distinct from adult calm theme)
- Header: "Hi! What do you want to do?"
- 4 activity tiles:
  - Watch a cartoon (tap to play 3-minute clip)
  - Colour a picture (interactive colouring with finger)
  - Play a matching game
  - Listen to a story
- Parent controls: "Parent lock" icon in top corner

---

## Screen 10: Companion Link Screen (Bonus Feature)
**Purpose:** Link caregiver's phone to patient's token.  
**Elements:**
- Patient sees: "Share your alerts" — generates a 6-digit code
- Companion opens app → "Enter companion code" → enters code → linked
- Confirmation: "Ishant Vishwakarma's phone is now linked. They will receive the same alerts as you."
- Linked companion shown as avatar at bottom of patient's home screen

---

## Screen 11: Feedback Section (Feature 5)
**Purpose:** Post-visit experience rating.  
**Elements:**
- Title: "How was your wait today?"
- Stress before wait: emoji slider (1–5)
- Stress after using CareEase: emoji slider (1–5)
- Most helpful feature: multi-select chips (Queue Tracker / Breathing / Distraction / Notifications / Nothing)
- Star rating (1–5 overall)
- Optional open text: "Anything you'd like to tell us?"
- Submit button → Thank you screen with teal tick

---

## Screen 12: Thank You / Post-Submission
**Purpose:** Positive close to the experience.  
**Elements:**
- Large teal tick icon
- "Thank you, Jitendra. Your feedback helps us improve."
- Stat shown: "Today, CareEase helped 247 patients feel calmer."
- "Book your next appointment" button
- "Rate us on the Play Store" link

---

## User Flow Diagram

```
LAUNCH → Language Select → Accessibility Setup
     ↓
Token Entry → Home Dashboard
     ↓              ↓
Mood Check-In    Relax & Explore
     ↓              ↓
Mood Response   Breathing / Kids / Sounds / Videos
     ↓
         ← ← SILENT NOTIFICATION (when turn near) → →
                        ↓
                "I'm on my way" → Counter
                        ↓
                   Feedback Form
                        ↓
                    Thank You Screen
```

---

## Clickable Prototype Link
> **[Add your Figma prototype link here before submission]**  
> Format: `https://www.figma.com/proto/[your-link]`

---

## Prototype Screenshots
> Screenshots of each screen are saved in the `/Wireframes` folder of this repository.  
> File naming: `screen_01_splash.png`, `screen_02_registration.png`, etc.
