# Testing Report — CareEase Hospital Queue App
## Design Thinking | Test Stage
**Prototype Version Tested:** V1 (Figma clickable prototype)  
**Test Date:** April 2025  
**Testers:** 8 volunteers from original research group  
**Testing Method:** Moderated usability test — each tester navigated prototype independently while being observed

---

## Testing Objectives

1. Can users find their queue position quickly on the home screen?
2. Do users understand how to access the Distraction Hub?
3. Is the Mood Check-in intuitive and comfortable?
4. Do users notice and understand the silent notification system?
5. Can elderly users navigate the app without assistance?
6. Does the app reduce perceived stress during the waiting experience?

---

## Test Participants

| ID | Name | Age | Role | Tech Level |
|----|------|-----|------|------------|
| T01 | Jitendra Sahani | 40 | Patient | Medium |
| T02 | Gudiya Sahani | 39 | Companion | Low-Medium |
| T03 | Madhuri Sahani | 15 | Companion (teen) | High |
| T04 | Aaron D'Souza | 21 | Patient | Very High |
| T05 | Arhaan Khan | 19 | Patient | High |
| T06 | Ishant Vishwakarma | 18 | Caregiver | High |
| T07 | Sudiksha Mourya | 17 | Patient | High |
| T08 | Priya Mehta | 65 | Patient (elderly) | Low |

---

## Task Scenarios Given to Testers

1. "You have just registered at the hospital. Open the app and find out how long you will wait."
2. "You are bored. Find something calming to watch or listen to."
3. "Rate how you are feeling right now using the app."
4. "Your notification says your turn is coming. What do you do?"
5. "After your appointment, fill in your feedback."
6. *(For Ishant only)* "Link your phone to your grandmother's token so you receive her alerts."

---

## Observation Notes

### T01 — Jitendra Sahani (40, M)
**Completed tasks:** 1, 2, 3, 4, 5  
**Observations:**  
- Found queue tracker immediately and smiled — said "finally, I can see my number"
- Struggled slightly to find Distraction Hub (expected it to be called "Timepass" or "Entertainment")
- Took 3 seconds to understand the mood slider — asked "is 1 good or 1 bad?"
- Pressed notification banner correctly and navigated to counter screen
- Filled feedback without issues; appreciated the Hindi option

**Feedback quote:**  
*"This is very good. If real hospitals had this, I would not feel like a ghost anymore."*

**Issues flagged:** Mood scale direction was confusing (1 = calm or 1 = stressed?), Distraction Hub label unclear

---

### T02 — Gudiya Sahani (39, F)
**Completed tasks:** 1, 2, 3  
**Observations:**  
- Had difficulty reading English labels — immediately switched to Hindi
- Queue tracker was clear once in Hindi
- Could not find Distraction Hub independently — needed prompting
- Mood check-in: hesitated, then understood after reading Hindi version
- Did not attempt feedback form — said it looked like too many steps

**Feedback quote:**  
*"In Hindi it is much better. The other one I could not read."*

**Issues flagged:** Distraction Hub icon not intuitive; feedback form too long for low-literacy users

---

### T03 — Madhuri Sahani (15, F)
**Completed tasks:** 1, 2, 3, 4, 5 (completed all fastest of all testers — 4 minutes total)  
**Observations:**  
- Navigated everything independently without any issues
- Loved the Kids Zone — said "this would've been great when I was younger"
- Wanted dark mode option
- Suggested adding short Reels-style videos to Distraction Hub

**Feedback quote:**  
*"It's nice but a bit too calm for teenagers. We want something more fun too."*

**Issues flagged:** Wants dark mode; content in Distraction Hub too calm/boring for teens

---

### T04 — Aaron D'Souza (21, M)
**Completed tasks:** All 5, plus explored extra features  
**Observations:**  
- Immediately appreciated the queue tracker design
- Compared it to Zomato delivery tracker — "same concept, why didn't hospitals think of this?"
- Tested edge cases: what if app connection drops? Noticed no offline state message
- Suggested adding "share with family" directly from queue screen
- Feedback form: completed and added long text suggestion

**Feedback quote:**  
*"This is actually really good. You need to add an offline fallback message though."*

**Issues flagged:** No offline mode indicator; queue screen needs "share" button

---

### T05 — Arhaan Khan (19, M)
**Completed tasks:** 1, 2, 3, 4, 5  
**Observations:**  
- Completed all tasks smoothly
- Very engaged with the guided breathing screen — said it genuinely helped
- Wanted music to play in background while he checked queue position
- Notification screen was very clear — thumbs up

**Feedback quote:**  
*"The breathing thing — I actually felt calmer after. That is the best feature for me."*

**Issues flagged:** Music should play in background across screens (not stop when leaving Distraction Hub)

---

### T06 — Ishant Vishwakarma (18, M)
**Completed tasks:** All 5 + Companion Link (Task 6)  
**Observations:**  
- Found Companion Link — slight confusion on where to enter the code
- Once linked, notification on second phone was very satisfying — said "this is exactly what I needed"
- Emotional response: clearly relieved when he saw how alerts would work
- Suggested making Companion Link more prominent — not buried in settings

**Feedback quote:**  
*"If my grandmother had this, I could relax a little. Right now I am always on edge. This would change that."*

**Issues flagged:** Companion Link buried in settings — should be on home screen or registration step

---

### T07 — Sudiksha Mourya (17, F)
**Completed tasks:** 1, 2, 3, 4, 5  
**Observations:**  
- Navigated smoothly and independently
- Appreciated calm colour palette — "it actually feels peaceful"
- Wished for a "quiet zone nearby" indicator showing if there's a calmer area in hospital
- Completed feedback quickly

**Feedback quote:**  
*"I like that it is not flashy. It feels like it cares about you."*

**Issues flagged:** Wants a feature to find quiet areas in hospital

---

### T08 — Priya Mehta (65, F)
**Completed tasks:** 1 (with assistance), 3 (with assistance)  
**Observations:**  
- Struggled significantly with standard text size — needed Accessibility Mode turned on first
- Once Accessibility Mode was activated: navigated queue tracker independently — huge improvement
- Mood check-in: confused at first, then understood with Hindi and large text
- Could not complete Distraction Hub or Feedback without help
- Silent notification: loved the concept — "finally someone thought of people like me"

**Feedback quote:**  
*"The big letters are good. But please — make the big letters come first, not after clicking somewhere."*

**Issues flagged:** Accessibility Mode must be default option during onboarding, not hidden; onboarding needs an "I need larger text" prompt on first launch

---

## Aggregated Feedback Scores

| Feature | Average Usefulness (1–5) | Average Clarity (1–5) |
|---------|--------------------------|----------------------|
| Queue Progress Tracker | 4.9 | 4.6 |
| Silent Pager Notifications | 4.8 | 4.5 |
| Distraction Hub | 4.2 | 3.8 |
| Mood-Based Interactions | 4.3 | 4.0 |
| Feedback Section | 3.9 | 3.7 |
| Companion Link (Bonus) | 4.7 | 3.9 |
| Multilingual Interface | 4.8 | 4.9 |
| Accessibility Mode | 4.9 | 3.5 |

**Overall app helpfulness rating: 4.4 / 5**  
**Overall stress reduction (before vs after using prototype): -1.6 points on 5-point scale**

---

## Iteration Log — Changes Made After V1 Testing

| Issue Found | Tester | Change Made in V2 |
|-------------|--------|-------------------|
| Mood scale direction confusing | T01 | Added clear labels: "1 = Very Calm" and "5 = Very Stressed" with emoji indicators |
| Distraction Hub label unclear | T01, T02 | Renamed to "Relax & Explore" — more intuitive |
| Feedback form too long | T02 | Reduced to 4 core questions; long version optional |
| No offline mode indicator | T04 | Added "You are offline — showing last known queue position" banner |
| Music stops when leaving screen | T05 | Background audio feature added — music continues across screens |
| Companion Link buried in settings | T06 | Moved Companion Link to registration step and home screen shortcut |
| Accessibility mode not default | T08 | Added "Set up accessibility" prompt on first launch for users 55+ |
| Teen content too calm | T03 | Added "Trending" section in Distraction Hub with short video content |

---

## Post-Iteration (V2) Testing Summary

After implementing changes, 5 testers (T01, T02, T04, T06, T08) were asked to re-test key screens.

- T01: Now found Distraction Hub immediately — "Relax & Explore" label clicked
- T02: Feedback form now completed independently
- T04: Appreciated offline banner — "now I know what the app will do if Wi-Fi fails"
- T06: Companion Link on home screen — "much better, I see it right away"
- T08: Accessibility prompt on first launch — completed setup independently — "this is how it should be"

**Post-iteration satisfaction score: 4.7 / 5**

---

## Final Conclusions

The CareEase prototype successfully addresses the core problem — eliminating uncertainty and reducing anxiety in hospital waiting rooms. The Queue Progress Tracker and Silent Pager features received the highest ratings across all user groups. The most significant learning was around accessibility: it must be a first-class feature, not a hidden setting. The iteration from V1 to V2 resulted in measurable improvement in both usability and user satisfaction across all age groups.
