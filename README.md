# Product-management-milestone-3
Product research project exploring why students and job seekers in India prefer typing over voice input on ChatGPT.
# 🎙️ Increasing Voice Input Adoption for ChatGPT

## Product Management Fellowship — Milestone 3

**Project:** From Insight to Solution  
**Product:** ChatGPT  
**Focus:** Increasing Voice Input Adoption  
**Target Segment:** Students & Job Seekers  
**Age:** 18–27  
**Market:** India  
**Platform:** Android / Mobile-first  
**Sprint:** 2 Weeks  
**Author:** Simran  
**Cohort:** 52

---
## 📊 Milestone 3 — From Insight to Solution
**[Milestone3_Voice_Input_Adoption_Deck.pdf](https://github.com/user-attachments/files/33030105/Milestone3_Voice_Input_Adoption_Deck.pdf)

**Click the presentation cover above to view the complete 13-slide deck.

# 📌 Project Overview

This project focuses on understanding why mobile users in India continue to type instead of using voice input on ChatGPT, and then translating those user insights into a focused product solution.

The project follows a complete product-thinking process:

**User Research → Problem Discovery → Problem Framing → Hypotheses → Solution Exploration → Prioritization → User Flow → Wireframes → Metrics → Experimentation**

The selected user segment is:

> **Students and job seekers aged 18–27 in India who primarily use ChatGPT on Android/mobile devices.**

---

# 🎯 Problem Statement

Many users rely on ChatGPT for tasks that can require significant typing, such as:

- Learning
- Searching for information
- Writing
- Job preparation
- Interview preparation
- Brainstorming
- Problem solving

However, despite having access to voice input, many users still prefer typing.

The key question was:

> **Why are users not adopting voice input on ChatGPT even when voice could make interaction faster and easier?**

---

# 🔎 Milestone 2 — Research Recap

The first stage of the project focused on understanding user behavior and identifying the underlying problems behind low voice adoption.

A survey was conducted with **31 respondents** from the target segment.

## 📊 Key Research Findings

### Current Input Behavior

- **54.8%** almost always type
- **9.7%** mostly use voice
- **0%** always use voice

This showed a significant gap between the availability of voice input and actual user adoption.

---

# 🚧 Major Voice Adoption Barriers

The research identified three major blockers.

## 1. Social Self-Consciousness

Users often avoid speaking when other people are nearby.

Voice usage was more comfortable when users were:

- Alone at home
- In a private environment

Users were less comfortable using voice in:

- College
- Office
- Around family
- Around friends
- Public/shared spaces

This suggests that voice input is not only a usability problem but also a social-context problem.

---

## 2. Low Trust in Voice Accuracy

Users expressed concerns that ChatGPT might misunderstand:

- Their pronunciation
- Their accent
- Their Hindi
- Hinglish
- Regional language
- Code-mixed speech

Around **32.3%** of survey respondents indicated concern that voice input may misunderstand what they say.

Approximately **65%** were concerned about accent/pronunciation.

Approximately **68%** wanted better support for:

- Hindi
- Hinglish
- Regional languages
- Mixed-language conversations

---

## 3. Lack of Live Feedback

Users did not have enough confidence about what ChatGPT had actually understood before sending their message.

Without visible live feedback, users had to trust the system completely.

This created uncertainty:

> "Did ChatGPT understand what I actually said?"

---

# 🧠 Core User Insight

The research indicated that users are not necessarily rejecting voice because they dislike speaking.

Instead:

> **Voice does not feel safe, accurate, or controllable enough in the situations where users need ChatGPT.**

Typing remains the default because users feel more control over what they send.

---

# 🧩 Problem Framing

The target users rely on ChatGPT for effortful tasks but continue typing because voice input does not provide enough confidence or control in shared environments.

### Root Hypotheses

The research resulted in four key hypotheses:

1. Users feel socially self-conscious while speaking around others.
2. Users have low trust in recognition of Indian accents and Hinglish.
3. Users lack real-time visibility into what the system is understanding.
4. Typing has already become an established default behavior.

---

# 💡 Milestone 3 — From Insight to Solution

Milestone 3 focused on converting the research insights into potential product solutions.

Three solution directions were explored.

---

# 💡 Solution Direction A — Live Transcript + Edit Before Send

### Concept

Introduce a real-time transcript while the user is speaking.

The user can:

- See what ChatGPT is understanding
- Review the transcript
- Correct mistakes
- Switch language
- Edit before sending
- Decide when the message is actually sent

### Key Principle

> **Nothing is sent until the user says so.**

### Problems Addressed

- Accuracy distrust
- Lack of live feedback
- Fear of sending an incorrect message
- Lack of user control

### Expected Benefit

Users gain confidence because they can see and correct the interpreted message before ChatGPT receives it.

---

# 💡 Solution Direction B — Ambient / Home-Screen Entry

### Concept

Make voice input easier to access through:

- Home-screen shortcut
- Lock-screen shortcut
- Faster voice entry

### Problem Addressed

This direction targets the discoverability and accessibility gap.

### Trade-off

It could increase voice usage, but requires more platform-level effort and introduces a higher implementation complexity.

---

# 💡 Solution Direction C — Regional & Accent Confidence Mode

### Concept

Allow users to select or configure their preferred:

- Accent
- Dialect
- Language
- Hinglish preference

Potential UI elements could include:

> "Tuned for Hinglish"

or a preferred-language/accent setup during onboarding.

### Problems Addressed

- Accent distrust
- Regional-language concerns
- Hinglish recognition concerns

---

# ⚖️ Solution Prioritization

| Direction | Impact | Effort | Confidence |
|---|---|---|---|
| A. Live Transcript + Edit | High | Medium | High |
| B. Ambient/Home Screen | Medium–High | High | Medium |
| C. Regional Accent Mode | Medium | Medium–High | Medium |

---

# 🏆 Chosen Solution

## Direction A — Live Transcript + Edit Before Send

This solution was selected as the first direction to build.

### Why?

It directly addresses the strongest problems identified during research:

- Accuracy concerns
- Lack of feedback
- Lack of control

It also avoids requiring:

- A new operating-system surface
- Major speech-model changes
- Immediate accent-model investment

Therefore, it represents the shortest path from:

**Typing Default → Confident Voice Flow → Repeatable Voice Usage**

---

# 🚫 What We Are NOT Building Yet

The first experiment intentionally keeps the scope focused.

### Not included in the first version:

- Home-screen voice shortcut
- Lock-screen voice shortcut
- Major speech-model changes
- Voice output changes

The response remains text-based, which is useful for users in shared environments.

---

# ⚠️ Honest Product Limitation

A live transcript cannot make a noisy environment quieter.

Instead, the solution reduces the consequences of speaking softly or being misunderstood because:

> **Nothing is sent until the user reviews and confirms the message.**

The solution should be evaluated carefully.

If:

- Time-to-send becomes worse than typing
- Correction rates remain flat after four weeks

then **Solution C — Regional & Accent Confidence Mode** should become the next priority.

---

# 👤 Target User

### Primary Segment

**Students & Job Seekers**

### Demographics

- Age: 18–27
- Location: India
- Device: Android
- Usage: Mobile-first

### Typical Use Cases

Users may use ChatGPT for:

- Learning
- Assignments
- Interview preparation
- Job search
- Resume preparation
- Skill development
- Writing
- Research
- Brainstorming

---

# 🔄 Proposed User Flow

## Existing User

**ChatGPT → Mic Icon → Permission / Language → Speak → Live Transcript → Review → Correct / Switch Language → Send → ChatGPT Response**

---

## Returning User

For returning users, the flow becomes simpler:

**ChatGPT → Mic → Speak → Review → Send → Response**

This reduces unnecessary friction after the user has already configured voice preferences.

---

# 🖥️ Proposed Experience

## Screen 1 — Entry Point

The user taps the existing microphone icon.

The experience begins from the existing ChatGPT interface rather than introducing a completely new interaction surface.

---

## Screen 2 — Live Transcript

While the user speaks:

- The transcript appears in real time.
- The user can see what the system is hearing.
- Low-confidence words can be highlighted.
- The user can identify possible recognition errors.

---

## Screen 3 — Review & Edit

Before sending, the user can:

- Read the complete transcript
- Edit incorrect words
- Correct misunderstood phrases
- Switch language
- Review the final message

### Important Principle

> **Nothing is sent until the user confirms.**

---

## Screen 4 — Sent & Answered

Once the user taps Send:

1. The final text is submitted.
2. ChatGPT processes the message.
3. The normal ChatGPT response is displayed.

This keeps the existing ChatGPT response experience unchanged.

---

# 🛠️ Failure States & Edge Cases

## Mic Permission Denied

If microphone permission is denied:

→ Show keyboard fallback.

The system can re-offer voice after approximately three sessions.

---

## User Speaks Too Quietly

The system should:

- Listen for approximately 3 seconds
- Continue the experience
- Allow the user to review

The message should **never be silently discarded**.

---

## Noisy Environment

If the environment is noisy:

- Continue showing the transcript
- Allow review
- Prompt the user to switch language or record again when needed

---

## User Taps Away

If the user exits the voice interaction:

→ Save the transcript as a draft in the message bar.

This prevents users from losing their work.

---

# 📊 Success Metrics

## North Star Metric

### Voice Send-Through Rate

The primary measure of whether users successfully move from:

**Voice Attempt → Review → Send**

---

# 📈 Proposed Metrics

| Metric | Current Baseline | Target |
|---|---:|---:|
| Mic tap rate | ~10% | 20% |
| Voice attempts reaching Send | Not tracked | 75% |
| Corrections per sent voice message | New metric | Falling over 4 weeks |
| Voice messages / active voice user / week | Not tracked | 3+ |
| Week-4 retention | Not tracked | Voice ≥ text-only |
| Hindi/Hinglish vs English send-through gap | Not tracked | <10 points |

### Important Note

The current baselines are directional because they are derived from a survey sample of **31 users**.

They should be re-established using actual product analytics before making final business decisions.

---

# 🛡️ Guardrail Metrics

The product should also protect against negative user experience.

### Guardrails

- Caption latency should be approximately **<300 ms/word**
- Voice time-to-send should not exceed typing
- No increase in overall session abandonment
- No decline in messages per session

---

# ⚠️ Product Risks

## Risk 1 — Review Friction

Users may find reviewing the transcript slower than typing.

### Mitigation

Measure:

- Time-to-send
- Correction rate
- Abandonment

---

## Risk 2 — Confidence Score Accuracy

A confidence indicator may not always accurately represent recognition errors.

### Validation

Sample approximately **200 transcripts** and compare system confidence against human-verified ground truth.

---

## Risk 3 — Social Self-Consciousness Remains

Even with a transcript, users may still avoid speaking around others.

### Validation

Interview users who:

- Open voice
- Start speaking
- Then abandon the interaction

---

## Risk 4 — Small Research Sample

The initial survey contains only **31 respondents**.

Therefore, the survey should not be treated as a definitive representation of all Indian ChatGPT users.

The next stage should validate findings through:

- Product analytics
- Additional interviews
- Larger research samples

---

# 🧪 Experiment Plan

## Experiment Duration

**4 weeks**

## Audience

- Android users
- India
- Age 18–27

## Experiment Split

**50/50 A/B test**

### Control Group

Existing ChatGPT voice experience.

### Treatment Group

New:

**Live Transcript + Review + Edit Before Send**

---

# 🎯 Primary Experiment Metric

### Voice Send-Through Rate

Measure the percentage of voice attempts that successfully reach the Send action.

---

# 🚨 Rollback Condition

The experiment should be rolled back if:

> **Overall session abandonment increases significantly because of the new voice review experience.**

---

# 🔁 Next-Step Decision

### If Solution A Works

Proceed to:

**Direction B → Ambient / Home-Screen Voice Entry**

Then evaluate:

**Direction C → Regional & Accent Confidence Mode**

### If Solution A Does Not Work

If:

- Time-to-send becomes worse than typing
- Correction rates remain flat
- Voice adoption does not improve

then prioritize:

**Regional & Accent Confidence Mode**

---

# 🧭 Product Strategy

The overall product strategy is:

```text
Understand User Behavior
        ↓
Identify Adoption Barriers
        ↓
Frame the Core Problem
        ↓
Generate Multiple Solutions
        ↓
Prioritize Based on Impact & Effort
        ↓
Build the Highest-Confidence Direction
        ↓
Measure User Behavior
        ↓
Run Experiment
        ↓
Iterate

---

# 🎞️ Milestone 3 Presentation

## Presentation Preview

[![Milestone 3 Presentation](./Milestone3_Slide_01.png)](./Milestone3_Voice_Input_Adoption_Deck.pdf)

**Click the presentation cover above to view the complete Milestone 3 presentation.**

### 📄 Full Presentation

[👉 View Milestone 3 Presentation](./Milestone3_Voice_Input_Adoption_Deck.pdf)

---

# 👩‍💻 About Me

**Simran**  
Product Management Fellowship — Cohort 52

This project is part of my Product Management Fellowship journey, where I am developing skills in:

- User Research
- Problem Discovery
- Product Thinking
- Solution Design
- Product Strategy
- Metrics & KPIs
- Experimentation
- Data-driven Decision Making

---

# 🔗 Connect With Me

## LinkedIn

[👉 Visit My LinkedIn Profile](www.linkedin.com/in/simran-45168a2a6)

![LinkedIn QR Code](./LinkedIn_QR_Simran.png)

---

## 💻 GitHub

[👉 Visit My GitHub Profile](https://github.com/Simran0913)

---

⭐ **Thank you for visiting my project!**
