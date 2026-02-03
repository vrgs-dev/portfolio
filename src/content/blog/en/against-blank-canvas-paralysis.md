---
title: 'Against the blank canvas paralysis'
description: 'A Claude Code skill that turns vague ideas into defined products. Discovery, Definition, Delivery.'
date: 2026-01-29
lang: en
translationKey: pm-skill-thinking-product
repoURL: 'https://github.com/vrgs-dev/pm-skill'
---

![PM-SKILL Agent](/media/blank-canvas-paralysis/banner.png)

Building is the easy part. **Knowing what to build is what hurts.**

I've spent years jumping between APIs and side projects.
My natural workflow has always been: _idea → code_. It's comfortable, it's tangible, and it gives you a false sense of progress.

But there's a pit I keep falling into: **the inability to think about the product out loud before writing the first line of code.**

I'm not talking about system architecture. I'm talking about facing the uncomfortable truth:

- Am I solving a real problem, or do I just like the technology I'm about to use?
- What is the minimum that delivers real value today?
- Why should anyone care about this?

When ideas live only in your head, they're perfect.
When you try to ground them, they turn into **noise**. And noise is the graveyard of projects that never made it to production.

---

## The void between the idea and the ticket

We have plenty of tools for when the path is already defined.
If you have a backlog, you have Jira. If you have a plan, you have Notion.

But **what do you have when all you have is doubt?**

That early stage is fragile. There are no frameworks that can save you from the initial chaos, and that's exactly where most of us give up or worse, build something nobody needs.

**PM-SKILL was created to fill that void.** It's a skill built for [Claude Code](https://docs.anthropic.com/en/docs/claude-code), Anthropic's CLI, that turns Claude into a product thinking sparring partner.

---

## Not an app, but a mental process

PM-SKILL didn't start on a design board. It started with frustration: current LLMs are great at writing code, but mediocre at challenging your product thinking unless you guide them carefully.

I asked myself: _What if AI could be the sparring partner that forces you to think?_

I don't want a bot that generates a generic PRD. I want a capability, a **skill** that integrates directly into my terminal, that can:

1. **Filter the noise:** Help separate "cool" features from necessary ones.
2. **Challenge the premise:** Ask who would actually feel pain if this project didn't exist.
3. **Structure the chaos:** Turn a messy note into a testable hypothesis.

---

## How it works: three phases, one command

PM-SKILL follows a three-phase methodology. You trigger it with a single command inside Claude Code:

```bash
/pm-skill
```

The skill auto-detects your current phase and runs the right one:

### 1. Discovery: understand before proposing

Claude asks direct questions to extract what's actually in your head. No assumptions, no premature solutions. Just clarity about users, goals, and constraints.

### 2. Definition: synthesize into a one-page brief

Using information from Discovery, the skill generates a concrete brief with the MVP defined through MoSCoW prioritization (Must / Should / Could / Won't). This is where you draw the line between necessary and nice-to-have.

### 3. Delivery: from features to user stories

Approved features get converted into user stories with acceptance criteria, grouped into deployable releases, each with a clear validation checkpoint.

Four non-negotiable rules guide the entire process: **ask before proposing**, **clarify before deciding**, **document before implementing**, and **validate before advancing**.

---

## Installing in Claude Code

PM-SKILL installs as a global skill in Claude Code. One script and you're set:

```bash
git clone https://github.com/vrgs-dev/pm-skill.git
cd pm-skill
bash install.sh
```

The installer copies the skill to `~/.claude/skills/pm-skill/` and optionally registers the `/pm-skill` command. It's also compatible with Cursor.

Once installed, open Claude Code in any project and type `/pm-skill`. The skill detects your context and starts the corresponding phase.

---

## A copilot for Day 0

I like to think of PM-SKILL as that senior colleague who doesn't give you answers, but asks the questions you've been avoiding.

It's not here to replace a Product Manager. It's here to **unblock** one. Especially in workflows where there are no assigned tasks, no roadmaps, no tickets. Just you, Claude Code, and an idea waiting to be shaped.

That's why it's a **skill**, not a closed platform. It lives where you work: in your terminal, inside Claude Code, adding a layer of product judgment where there used to be empty prompts.

---

## Building to think better

PM-SKILL is, today, an honest experiment. It's small, open, and constantly evolving.

Its goal isn't perfection — it's **clarity**.
An invitation to stop shipping for the sake of shipping and start using technology to make better decisions from day one.

If you've ever let an idea die because you didn't know where to start, [PM-SKILL](https://github.com/vrgs-dev/pm-skill) is for you.
