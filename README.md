# Product-management-milestone-3
Product research project exploring why students and job seekers in India prefer typing over voice input on ChatGPT.

# 🎙️ Increasing Voice Input Adoption for ChatGPT

## Product Management Fellowship — Milestone 3

> **From Insight to Solution — Turning user research insights into a focused product solution, measurable experiment, and product strategy.**

---

## 📌 Project Overview

This project focuses on increasing voice input adoption among **students and job seekers aged 18–27 in India** who primarily use ChatGPT on Android/mobile devices.

Milestone 3 builds on the user research conducted in Milestone 2 and moves from **problem discovery to solution design**.

| | |
|---|---|
| **Product** | ChatGPT |
| **Target Segment** | Students & Job Seekers, 18–27 |
| **Platform** | Android / Mobile-first |
| **Market** | India |
| **Author** | Simran |
| **Fellowship** | Product Management Fellowship |
| **Cohort** | 52 |
| **Sprint** | 2 Weeks |

---

## 📑 Presentation

### 🎥 Milestone 3 Presentation Deck

**[📊 View Milestone 3 Presentation — Voice Input Adoption](https://github.com/user-attachments/files/33030105/Milestone3_Voice_Input_Adoption_Deck.pdf)**

The presentation covers the complete product journey from:

**User Research → Problem Discovery → Solution Exploration → Prioritization → Product Strategy → Experimentation**

---

# 🎯 Product Problem

Voice input is already available in ChatGPT, but many users continue to type.

The core question explored in this project is:

> **Why do users continue typing instead of using voice input, even when voice could make interaction faster and easier?**

The research showed that the problem is not simply the availability of voice.

Users hesitate because voice does not always feel:

- Safe
- Accurate
- Controllable

especially in shared and on-the-go environments.

---

# 🔎 Milestone 2 Research Recap

The project started with user research focused on understanding why mobile users in India type instead of speaking to ChatGPT.

A survey was conducted with:

### **31 respondents**

## 📊 Key Behaviour Findings

| Behaviour | Result |
|---|---:|
| Almost always type | **54.8%** |
| Mostly use voice | **9.7%** |
| Always use voice | **0%** |

### Key Insight

> **Voice is not unavailable — it does not feel safe, accurate, or controllable in the shared, on-the-go places where this segment actually uses their phone.**

---

# 🚧 Three Major User Blockers

## 1. Social Self-Consciousness

Speaking out loud around:

- Classmates
- Family
- Friends
- Office colleagues
- People in public spaces
- Crowded environments

can feel uncomfortable or exposing.

Users are significantly more comfortable using voice when they are alone.

---

## 2. Low Trust in Accuracy

Users are concerned that ChatGPT may misunderstand their:

- Accent
- Pronunciation
- Hindi
- Hinglish
- Regional language
- Code-mixed speech

### Research Finding

**32.3%** of respondents said ChatGPT may misunderstand their voice.

This creates hesitation before using voice input.

---

## 3. No Live Feedback

Users cannot clearly see what ChatGPT has understood before the message is sent.

This creates uncertainty:

> **"Did ChatGPT understand what I actually said?"**

One respondent specifically suggested showing text while speaking.

---

# 🧠 Core Product Insight

The research suggests that users are not necessarily rejecting voice itself.

Instead:

> **Users need more confidence that their spoken input will be understood correctly and that they can control what gets sent.**

Typing remains the safer default because users can immediately see, edit, and control what they are sending.

---

# 🧩 Problem Framing

## Target User

Students and job seekers aged **18–27** who use ChatGPT frequently on Android/mobile devices.

## User Context

Users interact with ChatGPT for effortful tasks such as:

- Studying
- Job preparation
- Interview preparation
- Writing
- Resume preparation
- Research
- Brainstorming

These interactions often happen:

- At college
- At work
- During commuting
- Around family
- In shared environments

---

# 💡 Solution Exploration

Three possible product directions were explored.

---

# A — Live Transcript + Edit Before Send

## Concept

Show a real-time editable transcript while the user speaks.

Users can:

- See what is being recognized
- Identify possible recognition errors
- Correct words
- Switch language
- Review the message
- Edit before sending

### Targets

- Accuracy distrust
- Lack of live feedback
- Lack of user control

### Core Principle

> **Nothing is sent until the user confirms.**

---

# B — Ambient / Home-Screen Entry

## Concept

Provide a faster voice entry point through:

- Home-screen shortcut
- Lock-screen shortcut

This would allow users to start a voice interaction without first opening an existing ChatGPT conversation.

### Target

**Discoverability gap**

### Trade-off

It could improve access to voice but does not directly solve the underlying accuracy and trust problem.

---

# C — Regional-Accent Confidence Mode

## Concept

Allow users to select a preferred:

- Accent
- Dialect
- Language

The interface could communicate something such as:

> **"Tuned for Hinglish"**

### Target

**Distrust of code-mixed and regional-language recognition**

---

# ⚖️ Solution Prioritization

| Direction | Impact | Effort | Confidence |
|---|---|---|---|
| **A — Live transcript + edit-before-send** | High | Medium | High |
| **B — Ambient / home-screen entry** | Medium–High | High | Medium |
| **C — Regional-accent confidence mode** | Medium | Medium–High | Medium |

---

# 🏆 Chosen Solution

## Direction A — Live Transcript + Edit Before Send

Direction A was selected as the first solution to pursue.

### Why Direction A?

It directly addresses two of the strongest blockers identified during research:

1. Accuracy distrust
2. No live feedback

It also:

- Works inside the existing ChatGPT experience
- Does not require a new OS-level surface
- Does not require immediate accent-model investment
- Gives users more control
- Creates a shorter path from typing to confident voice usage

---

# 🚫 What We Are Not Building Yet

The first version intentionally does not include:

- Home-screen voice surface
- Lock-screen voice surface
- Changes to the speech model itself
- Voice output changes

The response remains text-based.

This is useful for users who are interacting with ChatGPT in shared environments.

---

# ⚠️ Honest Product Limitation

Social self-consciousness was identified as the biggest blocker.

A transcript cannot make a crowded environment quieter.

Instead, the transcript reduces the consequences of speaking softly or being misunderstood.

Nothing is sent until the user reviews the message.

Therefore:

> **A half-heard sentence becomes a correction opportunity instead of an incorrect message being sent.**

### What Would Change the Decision?

If:

- Time-to-send becomes worse than typing, or
- Correction rates remain flat after four weeks,

then **Direction C — Regional-Accent Confidence Mode** would move ahead.

---

# 👤 Target User

## Primary Segment

**Students & Job Seekers**

### Demographics

- Age: 18–27
- Market: India
- Device: Android
- Platform: Mobile-first

### Typical Use Cases

Users may use ChatGPT for:

- Studying
- Assignments
- Interview preparation
- Job search
- Resume preparation
- Skill development
- Writing
- Research
- Brainstorming

---

# 🔄 User Flow

The existing microphone icon remains the starting point.

### Proposed Flow

```text
Mic Icon
   ↓
Permission / Language
   ↓
Speak
   ↓
Live Transcript
   ↓
Review
   ↓
Correct / Switch Language
   ↓
Send
   ↓
Normal ChatGPT Response
```

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

Once the user taps **Send**:

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

## 📈 Proposed Metrics

| Metric | Current Baseline | Target |
|---|---:|---:|
| Mic tap rate | ~10% | **20%** |
| Voice attempts reaching Send | Not tracked | **75%** |
| Corrections per sent voice message | New metric | **Falling over 4 weeks** |
| Voice messages / active voice user / week | Not tracked | **3+** |
| Week-4 retention | Not tracked | **Voice ≥ text-only** |
| Hindi/Hinglish vs English send-through gap | Not tracked | **<10 points** |

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

## Voice Send-Through Rate

Measure the percentage of voice attempts that successfully reach the **Send** action.

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
```

This follows a product-management approach focused on:

- User Research
- Problem Discovery
- Product Thinking
- Solution Design
- Product Strategy
- Metrics & KPIs
- Experimentation
- Data-driven Decision Making

---

# 📚 Key Product Management Learnings

Through this project, I practiced:

### 🔍 User Research

Understanding user behaviour through surveys and qualitative insights.

### 🎯 Problem Framing

Moving beyond the surface problem of "users don't use voice" to understand the underlying trust, control, and social-context barriers.

### 💡 Solution Design

Generating multiple solutions rather than jumping directly to one feature.

### ⚖️ Prioritization

Comparing solutions based on impact, effort, and confidence.

### 📊 Metrics

Defining a North Star Metric, supporting metrics, and guardrails.

### 🧪 Experimentation

Designing an A/B experiment to validate whether the proposed solution changes user behaviour.

### 🔄 Iteration

Defining what evidence would cause the product team to change direction.

---

# 🚀 Future Opportunities

If the first experiment demonstrates positive results, future opportunities include:

1. **Ambient / Home-Screen Voice Entry**
2. **Regional & Accent Confidence Mode**
3. Improved Hinglish recognition
4. Better regional-language support
5. Personalized language preferences
6. Smarter confidence indicators
7. Voice experience personalization
8. More accessible voice interactions in low-connectivity environments

---

# 🎯 Final Product Hypothesis

> **If ChatGPT gives users real-time visibility and control over their spoken input before sending it, users will have greater confidence in voice interactions and will be more likely to adopt voice input for repeated mobile use.**

---

# 👩‍💻 About Me

### Simran

**Product Management Fellowship — Cohort 52**

I am building my skills in:

- Product Management
- User Research
- Product Strategy
- Problem Solving
- Product Analytics
- Data-driven Decision Making
- Experimentation

I enjoy exploring user problems, turning research insights into product opportunities, and designing measurable solutions.

---

# 🔗 Connect With Me

### LinkedIn

**[🔗 Connect with me on LinkedIn](www.linkedin.com/in/simran-45168a2a6)**

---

# 📑 Presentation

### Milestone 3 — Voice Input Adoption

**[📊 View the Complete 13-Slide Presentation]([Milestone3_Voice_Input_Adoption_Deck.pdf](https://github.com/user-attachments/files/33030564/Milestone3_Voice_Input_Adoption_Deck.pdf)
)**

---

## ⭐ Project Summary

**Research → Insight → Problem → Solution → Prioritization → Metrics → Experiment → Strategy**

> **The goal is not simply to make voice available. The goal is to make voice feel trustworthy, controllable, and useful enough for users to choose it over typing.**

---

### 👩‍💻 Created by Simran

**Product Management Fellowship — Cohort 52**

[🔗 LinkedIn Profile](https://lnkd.in/p/gdSVTvuj)
