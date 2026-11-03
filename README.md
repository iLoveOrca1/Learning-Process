<p align="center">
    <img src="https://github.com/iLoveOrca1/Learning-Process/tree/main/images/HTB.jpeg?raw=true" width="400" alt="HTB Logo">
    </a>
</p>

<p align="center">
    <a href="https://academy.hackthebox.com/app/module/9"><img src="https://img.shields.io/badge/hackthebox-room-green?style=for-the-badge"/></a>
    <a href="https://github.com/iLoveOrca1/Learning-Process"><img src="https://img.shields.io/badge/github-repo-blue?style=for-the-badge&logo=GitHub"/></a>
</p>

Summarized version for the module Learning Process from Hack The Box

It is very advised to read the Module "Learning Process" first before reading this summary in order to get a better understanding of how the learning process actually works in information security.

---

# HTB: Learning Process

Notes for CPTS prep and CTFs. The module is mostly about _how_ to learn and work, not tech. Each section ends with the part that matters for pentesting.

**TL;DR**

- Find the simplest explanation first (Occam).
- Set a specific goal. "Understand it" beats "finish it".
- Learn actively: practice and discuss, don't just read.
- Fear is about an imagined future. Check what's actually true right now.
- Document as you go, and organize before you start.
- The hard part isn't finding answers, it's asking the right question.

---

## 1. Mindset

**Way of thinking**

- You don't need to know every language to read code. They share the same principles (R. D. Tennent): Abstraction, Correspondence, Data Type Completeness.

**Occam's Razor**

- Among explanations that fit the facts, the simplest is usually the most likely.
- _Pentest use:_ check the obvious first (default creds, misconfig, known CVE) before building a complex theory.

**Talent**

- Nobody is born talented. Steady learning is what gets you ahead of yesterday's you.

> The art is not to get the flag, but to find the way to do it.

---

## 2. Learning Dependencies

### Think outside the box

`20 * ___ + ___ = 65535` has many valid answers. Don't limit yourself to one approach.

- A problem is an _emotional_ state. Without emotion, it's just a situation.
- Know your goal.

### Learning efficiency

Combine **knowledge + adaptation + new information**. To find what you need, ask:

- What do I already know?
- What don't I know yet?

Being good at something = knowing what you're doing.

### Passive vs active learning

![Learning Pyramid](./images/learningPyramid.jpg "Learning Pyramid")

| Type    | How                                                   | Retention |
| ------- | ----------------------------------------------------- | --------- |
| Passive | Reading                                               | ~10%      |
| Passive | Watching demos                                        | ~30%      |
| Active  | Discussing enumeration, results, findings with others | ~50%      |
| Active  | Practicing hands-on                                   | ~75%      |

- _Takeaway:_ labs and boxes over re-reading. Compare notes with others to catch what you missed.
- Progress shows up when the question that bothered you stops mattering.

### The brain

**Myths:** we use only 5-10% of our brain; learning speed = intelligence; Einstein was bad at math.

**Thought:** an individual reaction to internal/external influences, interpreted through your own personal methodology.

- **Conscious:** active awareness of yourself and your surroundings. You can choose to change what you're doing.
- **Unconscious:** emotions reflect subconscious thinking. We process far more subconsciously, and decisions are made before we notice them.
- Fun fact: the brain regions for the hardest logical tasks aren't fully developed until about 20 (±2).

### The will

- Will = deliberately deciding to act toward a goal.
- Most people quit early because they can't see the path. But **the path is created by the steps you take**, not planned in advance.
- **Fear** is a product of imagining the future while ignoring the present. Ask yourself:
    - Have I worked through the material yet?
    - Have I seen what's taught and how?
    - Do I already need the skills expected of me?
    - If all "no", you're afraid of something you haven't tried.

### The goal

- Specific, challenging goals work better (over 90% do better with them).
- Pick yours: pass an exam, get a cert, master a skill, or impress others?
- Your goal shapes how you think. "Complete the module" and "understand the module" give different results.
- Skipping your own thinking (not trying to solve it yourself) skips the associations your brain needs to learn.

> Efficiency conflicts with comfort.

### Decision making: the Trolley Problem

![Trolley Problem](./images/trolleyProblem.png "Trolley Problem")

Five people on the main track, one on the siding. Obvious options: switch or don't. The "solved" version uses ropes and pillars to stop the train.

![Trolley Problem Solved](./images/trolleyProblemSolved.png "Trolley Problem Solved")

- Nobody said we couldn't. **We set our own limits.**
- Ask facts first: How far is the train? How fast? How much time? What tools do I have?
- _Pentest use:_ "Out of scope" or "not allowed" often exists only in your head. Check the actual rules of engagement, not your assumptions.

**Summary chain:** Decision making → defined goal → willingness → the brain.

---

## 3. Learning Overview

### Documentation

Good docs have **overview, structure, clarity**. Tool suggested: **CherryTree**.

- Write for your reader (future you, or a client).
- Avoid repetition and ambiguity.
- Make it easy to read.

### Organization

You can compromise several systems in one day. You don't want to hunt for info each time.

- Woodcutter: the inexperienced one sharpens for 30 min and cuts for 3 hours. The experienced one sharpens for 3 hours and cuts for 30 min.
- Methods: Scrum, Agile, to-do lists, bullet journal.

---

## 4. The Process

### Focus vs attention

- **Attention:** what you're perceiving right now. Driven by interests, needs, beliefs, goals, experience. Happens subconsciously.
- **Focus:** deliberate alignment toward a goal. Driven by will.
- **Concentration:** keeping attention on one topic.
- Know your goal and focus follows, with less distraction.

### Comfort (Yerkes-Dodson)

![Yerkes-Dodson](./images/newYerkesDodsonLaw.png "The Yerkes Dodson Law")

- Leaving your comfort zone brings uncertainty, which lowers thinking ability and slows you down at first.
- Small children try new things without fear of mistakes. **Mistakes are part of learning.**
- People who push out of their comfort zone get there faster than expected.

![Comfort Zone](./images/theComfortZone.png "Comfort Zone")

### Obstacles

**Fear**

- Fear targets an imagined future and the consequences we calculate for it. More detail makes more fear.
- Will Smith talks about confronting his own fear: https://youtu.be/VsTBCQ2MnRM
- Ask: **"Which of these reasons are actually real right now?"**
- Past failures feed it. Remember: winners have simply lost more often than losers.
- Failure is unavoidable and essential. Nobody learns a skill without mistakes.

**Mindset: add "yet"**

- "I can't do this" → "I can't do this **yet**." Same for "not for me" and "don't understand".

**Comparison**

- Talent = strongly developed skill with high efficiency.
- Skill = ability to solve something well.
- Passion = emotional commitment to an area.
- Not everyone can be a great hacker, but a great hacker can come from anyone.

**Pressure**

- Stuck? Do something new that needs creativity. What you do matters less than that it's new.
- Criticism only stings from people whose opinion we value highly.
- A clear goal blocks outside influence.
- Only someone who took your exact journey can fairly judge you. The rest is assumption.

### 4.5 Questioning

> The hardest part of any situation is not finding the right answer, but finding the right question.

_Pentest use:_ before running tools, ask: what do I know about this target, what do I not know, what question gets me closer to a foothold?

---

## Quick checklist (for exam day / CTFs)

1. Goal: what exactly am I trying to get right now?
2. Known vs unknown: what do I have, what's missing?
3. Simplest explanation first.
4. Stuck? Ask a better question, or try a new approach.
5. Check limits against real rules, not assumptions.
6. Write it down as you go.
7. Failed attempt? That's data. Add "yet" and continue.