# CareEase — Smart Solutions for Hospital Queues
### Design Thinking for Innovation | Summative Assessment
**Student Name:** Aditya Jitendra Kumar Sahani  
**Candidate Number:** 1000414
**School** Aspee Nutan Academy
**CRS:** Artificial Intelligence  
**Course:** Design Thinking for Innovation  
**Scenario:** Scenario 2 — Create Smart Solutions for Hospital Queues  
**Institution:** World Academy of Career Programmes (WACP)  
**Assessment:** Summative Assessment


## Project Overview

CareEase is a conceptual mobile app prototype designed to transform the hospital waiting experience from one of anxiety, uncertainty, and discomfort — into one that is calm, engaging, and informative.

Developed using the Design Thinking process (Empathize → Define → Ideate → Prototype → Test), CareEase addresses a real and widespread problem: patients in hospital waiting rooms receive almost no information about their queue status, have nothing calming or meaningful to do, and vulnerable groups (elderly, hearing-impaired, parents with young children) are particularly underserved.

**Target Audience:** Hospital outpatients, inpatients, caregivers, and companions — across all ages and ability levels.

**Designed for:** CareEase Health Systems (fictional healthcare company)

---

## Problem Statement

> *"How might we transform the hospital waiting experience into a calm, engaging, and informative journey — for patients of all ages, abilities, and languages — by providing real-time queue transparency, inclusive accessibility features, and meaningful emotional support?"*

---

## Design Thinking Process

### Stage 1: Empathize & Define

**Research conducted with 12 participants** across age groups, visit types, and backgrounds. Methods used:
- In-person structured interviews
- Written survey (20 questions)
- Observation in hospital waiting areas

**Key Participants:**
| Name | Age | Role |
|------|-----|------|
| Jitendra Sahani | 40 | Patient — diabetes outpatient |
| Gudiya Sahani | 39 | Caregiver companion |
| Madhuri Sahani | 15 | Teenage companion |
| Aaron D'Souza | 21 | First-time visitor |
| Arhaan Khan | 19 | Follow-up patient |
| Ishant Vishwakarma | 18 | Caregiver for elderly grandmother |
| Sudiksha Mourya | 17 | Student — solo patient |
| Priya Mehta | 65 | Elderly cardiac patient |
| Ramesh Gupta | 58 | Chronic illness — orthopedic |
| Sneha Patil | 32 | Parent with young child |
| Karan Malhotra | 27 | Marketing professional — first visit |
| Lalita Devi | 70 | Hearing-impaired elderly patient |

**10 Detailed Personas Created** — see `/Docs/02_personas.md`  
**5 Empathy Maps Created** — see `/Docs/03_empathy_maps.md`  
**Problem Statement Defined** — see `/Docs/04_problem_statement_insights.md`

**Top Pain Points:**
1. Zero real-time queue information — patients are completely in the dark
2. Hearing-impaired patients miss their name calls
3. Nothing to do — complete absence of meaningful engagement
4. No child-friendly content or space
5. Language barriers (English-only displays in Hindi-speaking population)
6. Elderly users cannot navigate existing digital systems
7. Caregiver companions are entirely unsupported

---

### Stage 2: Ideate

**25+ ideas generated** using Crazy 8s brainstorming and Miro digital boards.  
Ideas prioritised using a 2x2 Impact vs Effort matrix.

**5 Compulsory Features Selected:**
1. Queue Progress Tracker
2. Distraction Hub (Relax & Explore)
3. Silent Pager Notifications
4. Mood-Based Interactions
5. Feedback Section

**3 Bonus Innovative Features:**
1. Companion Link — caregiver receives same alerts as patient
2. Multilingual Interface — Hindi and English toggle
3. Accessibility Mode — large text, high contrast, vibration-only alerts

Full ideation document: `/Docs/05_ideation_features.md`

---

### Stage 3: Prototype

**Tool:** Figma (clickable, mobile-first prototype)  
**Screens designed:** 12 screens with complete navigation flow

**Screens include:**
- Splash / Language / Accessibility Setup
- Patient Registration & Token Entry
- Home Dashboard with Live Queue Tracker
- Silent Pager Notification Screen
- Mood Check-In and Personalised Response
- Relax & Explore — Distraction Hub
- Guided Breathing Animation
- Kids Zone
- Companion Link Setup
- Feedback Form
- Thank You Screen

**Prototype Link:** [https://debug-ai-42935159.figma.site/]  
**Screen Guide:** `/Wireframes/prototype_screen_guide.md`  
**Screenshots:** `/Wireframes/` folder

**Design Principles Applied:**
- Calm teal/green colour palette (reduces visual anxiety)
- Minimum 16px font size (accessibility)
- Hindi and English on every screen
- Icon-based navigation for low-literacy users
- Accessibility mode available from first launch

---

### Stage 4: Test

**Testing conducted with 8 volunteers** from original research group  
**Prototype version tested:** V1 (Figma clickable)  
**Method:** Moderated usability observation + post-test survey

**Key Results:**
- Overall app helpfulness: **4.4 / 5**
- Perceived stress reduction: **-1.6 points** (before vs after using prototype)
- Queue Tracker satisfaction: **4.9 / 5**
- Silent Notifications clarity: **4.5 / 5**

**8 Iterations made from V1 → V2 based on user feedback:**
1. Mood scale labels clarified (1 = Calm, 5 = Stressed)
2. "Distraction Hub" renamed "Relax & Explore" for clarity
3. Feedback form shortened (4 core questions)
4. Offline mode indicator added
5. Background audio continues across screens
6. Companion Link moved to home screen (was buried in settings)
7. Accessibility Mode prompted at first launch
8. Trending/short video content added for teens

**Post-V2 satisfaction score: 4.7 / 5**

Full testing report: `/Docs/06_testing_report.md`

---

## Repository Structure

```
CareEase-AI-HospitalQueue/
│
├── README.md                          ← This file
│
├── Docs/
│   ├── 01_survey_research_report.md  ← Full survey data and findings
│   ├── 02_personas.md                ← 10 detailed user personas
│   ├── 03_empathy_maps.md            ← 5 empathy maps
│   ├── 04_problem_statement_insights.md ← Insights + problem statements
│   ├── 05_ideation_features.md       ← Brainstorm + 5 compulsory features
│   └── 06_testing_report.md          ← Testing observations + iterations
│
├── Wireframes/
│   ├── prototype_screen_guide.md     ← All 12 screens described in detail
│   ├── screen_01_splash.png          ← [Add Figma export screenshots]
│   ├── screen_02_registration.png
│   ├── screen_03_home_dashboard.png
│   ├── screen_04_silent_notification.png
│   ├── screen_05_mood_checkin.png
│   ├── screen_06_mood_response.png
│   ├── screen_07_distraction_hub.png
│   ├── screen_08_breathing.png
│   ├── screen_09_kids_zone.png
│   ├── screen_10_companion_link.png
│   ├── screen_11_feedback.png
│   └── screen_12_thankyou.png
│
└── Data/
    └── survey_responses.csv          ← Raw survey responses (12 participants)
```

---

## Technologies & Tools Used

| Category | Tool |
|----------|------|
| Prototyping | Figma |
| Brainstorming | Miro |
| Mind Mapping | MindMeister |
| Survey Collection | Google Forms (in-person assisted) |
| Data Organisation | Google Sheets |
| Documentation | Markdown (GitHub) |
| Version Control | GitHub |
| Design Reference | Material Design 3, Apple HIG |

---

## Demo & Screenshots

> **Figma Prototype:** [Add your Figma link here — make sure it is set to "Anyone with link can view"]  
> **Demo Video:** [Add Loom/YouTube link here if applicable]  
> **Screenshots:** See `/Wireframes/` folder for all 12 screen exports

---

## Key Learning & Reflection

This project demonstrated that the hospital waiting experience fails patients not because of a lack of technology — but because of a lack of empathy in system design. The research process, especially speaking with Ishant Vishwakarma (who brought his hearing-impaired grandmother) and Priya Mehta (elderly, anxious, alone), profoundly shaped the design decisions. The most impactful feature — silent notifications — was not in the original feature list. It emerged entirely from listening to real users.

Design Thinking is not a process of building what you assume people need. It is a discipline of listening carefully, questioning your assumptions, and letting real human experiences guide every decision.

---

*Submitted to WACP | CRS: Artificial Intelligence | Design Thinking for Innovation*  
*Repository: https://github.com/adityasahani392217/IDAI106-1000414-ADITYA-JITENDRA-KUMAR-SAHANI-SA*
