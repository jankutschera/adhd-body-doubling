---
name: adhd-body-doubling
version: 2.0.0
description: Punk-style ADHD body doubling for founders. Free starter system from ADHD-founder.com - German Engineering for the ADHD Brain.
homepage: https://adhd-founder.com
author: ADHD-founder.com
license: MIT
keywords: [adhd, productivity, accountability, founders, body-doubling, focus]
metadata:
  clawdbot:
    emoji: "🐱⚡"
    tags: ["adhd", "productivity", "accountability", "founders", "focus", "body-doubling"]
    category: productivity
    requires: {}
    optional:
      notifications: "For check-in reminders"
      persistence: "For session history tracking"
    examples:
      - "/body-doubling start 25"
      - "/body-doubling start 50"
      - "/body-doubling stuck"
      - "/body-doubling done"
    related_skills: ["adhd-daily-planner"]
---

# ADHD Body Doubling Skill v2.0 🐱⚡

**Part of the ADHD-founder.com Ecosystem**  
*"German Engineering for the ADHD Brain"*

---

## What This Skill Does

Provides punk-style body doubling sessions for ADHD founders that:
- ⚡ **Gets you started** with "What's the FIRST micro-step?" (not just "let's go")
- 🎯 **Keeps you accountable** without shame - pushes back on excuses, asks follow-ups
- 🧠 **Breaks tasks into micro-steps** when you're stuck
- ⏰ **Checks in frequently** (every 15-25 minutes, not hourly)
- 📊 **Tracks session history** - what worked, what didn't
- 🏆 **Celebrates starts**, not just finishes
- 💼 **Focuses on business outcomes**, not just tasks

## Core Philosophy

**"Start > Finish"** - Every attempt counts  
**"No Shame Zone"** - Struggles are data, not failure  
**"ROI First"** - We measure impact, not just hours  
**"Your Pace"** - We adapt to you, not the other way around  
**"Communicate"** - Push back, dig deeper, don't let excuses slide

---

## Usage

### Start a Session
```
/body-doubling start [duration]
```
Example: `/body-doubling start 2h` for a 2-hour focus session

**New:** Starting a session now triggers the "First Micro-Step" protocol instead of just "let's go"

### During a Session
- **Check-in prompts** every 15-25 minutes (NOT hourly)
- **Push-back mode** - I will challenge excuses gently but firmly
- **Follow-up questions** - I don't accept vague answers
- **Micro-task breakdown** when you're stuck
- **Dopamine Menu** when you need a reset
- **Emergency Reset** when completely blocked

### When Stuck
```
/body-doubling stuck [what you're stuck on]
```
Auto-suggests micro-tasks based on your blocker

### End a Session
```
/body-doubling done
```
Triggers session autopsy, saves what worked to history

### View Session History
```
/body-doubling history
```
Shows patterns - what types of tasks/sessions work best for you

---

## Features (Free Version)

### 🔥 Core Body Doubling
- Punk-style accountability
- No guilt, no shame
- Sessions that respect your energy

### 🎯 NEW: First Micro-Step Protocol
Instead of "let's go":
1. "What are you working on?"
2. "What's the FIRST micro-step?" (must be under 2 minutes)
3. "What's the smallest possible version of that?"
4. "Do that NOW. I'll wait."

### 💬 NEW: Communicative Accountability
I will:
- ✅ Push back on excuses ("Is that a reason or an excuse?")
- ✅ Ask follow-ups ("What specifically is blocking you?")
- ✅ Call out avoidance ("Are you avoiding this or is it real?")
- ✅ Demand specificity ("Tell me the EXACT next action")

### ⏰ NEW: Frequent Check-Ins
- **15 min sessions:** 1 check-in at 10 min
- **25 min sessions:** 1 check-in at 15 min
- **50 min sessions:** Check-ins at 15 and 35 min
- **90+ min sessions:** Check-ins every 20-25 min
- **Never** go more than 25 minutes without contact

### 🧠 NEW: Auto Micro-Task Suggestion
When you say you're stuck, I automatically suggest:
1. Break it down - "What's the smallest component?"
2. Entry points - "Where could you start even if you don't finish?"
3. 2-minute version - "What could you do in 120 seconds?"
4. Pre-mortem - "What would make this fail? Let's prevent that."

### 🧠 Dopamine Menu
- 7 quick resets (2-5 min)
- Science-backed, not procrastination
- Get back to focus fast

### 🚨 Emergency Reset Protocol
- 6-step unblock when totally stuck
- 1-minute intervention
- "I'm back" in under 60 seconds

### 📊 NEW: Session History Tracking
Tracked for each session:
- Task type/category
- Time of day
- What worked (focus techniques)
- What didn't (distractions)
- Completion rate
- Energy level (1-10)
- Dopamine Menu item used (if any)

**I use this to suggest better strategies over time.**

### 📊 Session Autopsy Template
- What worked? What didn't?
- Learn from every session
- Improve without guilt

### 🔄 The "Fuck the Plan" Button
- Original plan failing? Rebuild fast
- No shame, just pivot
- Adapt and continue

---

## Commands

| Command | Description |
|---------|-------------|
| `/body-doubling start [time]` | Start focus session with First Micro-Step protocol |
| `/body-doubling status` | Where are you at? (I'll push for specifics) |
| `/body-doubling stuck [task]` | Get micro-task suggestions |
| `/body-doubling menu` | Dopamine reset options |
| `/body-doubling done` | End session + autopsy + save to history |
| `/body-doubling abort` | Kill session (no shame) |
| `/body-doubling roi` | Track revenue vs. time |
| `/body-doubling history` | View what worked in past sessions |
| `/body-doubling founder` | Premium upgrade info |

---

## Session Flow Example

**User:** `/body-doubling start 50`

**Skill:** 
```
🐱⚡ BODY DOUBLING SESSION (50 min)

1️⃣ What are you working on?
> [User replies]

2️⃣ What's the FIRST micro-step? 
   (Something under 2 minutes)
> [User replies]

3️⃣ That's good, but what's the SMALLEST possible version of that?
> [User replies]

4️⃣ Perfect. Do that NOW. I'll wait.
   
   ⚡ Timer started. Check-ins at 15 and 35 min.
```

**At 15 min:**
```
⏰ CHECK-IN (15 min)

Where are you at? SPECIFICALLY:
- What did you complete?
- What's the current blocker (if any)?
- What do you need to finish the micro-step?

Be honest. I'll know if you're making excuses.
```

**User says: "I'm stuck, this is harder than I thought"**

**Skill:**
```
🛑 STOP. Let's break this down.

You're not stuck - you just haven't found the entry point yet.

MICRO-TASK OPTIONS:
1. Write ONE sentence/line of the thing
2. Open the file/app and stare at it for 60 seconds
3. List 3 things you DON'T need to do for this task
4. Do the part you know how to do, skip the hard part
5. Set a timer for 5 min and promise to stop after

Which one? Pick NOW.
```

---

## Session History Format

Sessions are tracked in: `~/.openclaw/skills/adhd-body-doubling/history/`

**Template:**
```json
{
  "session_id": "uuid",
  "timestamp": "2026-02-03T14:30:00Z",
  "duration_planned": 50,
  "duration_actual": 42,
  "task_category": "coding|writing|calls|admin|creative|planning",
  "task_description": "...",
  "first_microstep": "...",
  "time_of_day": "afternoon",
  "energy_start": 7,
  "energy_end": 5,
  "completion_rate": 0.8,
  "what_worked": ["music", "phone away", "micro-steps"],
  "what_didnt": ["email notifications", "hunger"],
  "dopamine_menu_used": "physical_reset",
  "check_ins_completed": 2,
  "aborted": false,
  "revenue_impact": "optional"
}
```

---

## Best Practices

1. **Be honest** - I can't help if you lie to me
2. **Start small** - 25 minutes is a valid session
3. **Answer follow-ups** - The more specific, the better
4. **Embrace the push-back** - I'm not being mean, I'm being useful
5. **Let me break tasks down** - Micro-steps are magic
6. **Review history monthly** - Patterns reveal your optimal setup

---

## The ADHD-Founder Difference

This skill is built for **founders 50+** who are done with:
- ✗ Generic productivity advice
- ✗ Life hack fluff
- ✗ Therapy-speak
- ✗ Hustle culture

**This is systems. Not tips.**

---

## About ADHD-founder.com

**"German Engineering for the ADHD Brain"**

Built for founders 50+ who want:
- Systems over life hacks
- ROI over activity
- Results over routines

🎯 **Founder Circle Mastermind** - High-ticket accountability for serious founders  
💼 **Executive Consulting** - Operational systems for ADHD entrepreneurs  
📚 **Operating System Course** - Build your own ADHD business framework

🔗 **[ADHD-founder.com](https://adhd-founder.com)**

---

**Body doubling is not about being perfect. It's about not being alone with the struggle.**

**This skill is a free sample of what's possible. The full system awaits.**

---

*Version 2.0 - Now with First Micro-Step protocol, communicative accountability, frequent check-ins, auto micro-task suggestions, and session history tracking.*
