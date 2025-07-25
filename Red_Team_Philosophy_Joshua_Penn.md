
# 🧠 Red Team Philosophy: Joshua Penn

## 🎯 Mission
To protect systems, users, and society by thinking like the adversary — exposing hidden assumptions, untested trust boundaries, and misaligned incentives before real attackers do. The microsoft SC-900 training course is what has me thinking in this area its a gold mine of insight.

---

## 🔐 Core Principles

### 1. **If It’s Trusted, It’s Exploitable**
Modern systems grant roles and permissions based on implicit trust:
- A user with credentials
- A device with a token
- An AI model trusted to answer questions

Red teaming asks: _“What if this identity isn’t who it appears to be?”_  
Every identity is a potential threat — even AI.

---

### 2. **AI is an Identity — Treat It Like One**
LLMs, chatbots, and ranking systems act **on behalf of the platform**.  
That makes them **high-trust agents** — like privileged users or APIs.

If you wouldn’t trust a junior employee to speak for your company without supervision, why trust an AI?

---

### 3. **Prompt Injection = Social Engineering for Machines**
Red teamers exploit LLMs the same way hackers exploit humans:
- Manipulate context
- Use reverse psychology
- Insert “trusted tokens” like emojis or tone
- Chain together believable lies until the AI responds inappropriately

This isn't hacking the model — it's hacking the system around it.

---

### 4. **Engagement vs. Safety is the Real Battle**
Most platforms reward engagement:
- Likes, replies, clicks, shares

Safety tools are bolted on later.  
This creates **incentive mismatch** — the model is trained to engage, not defend.

> “A helpful AI becomes dangerous when it’s more afraid of being boring than being wrong.”

---

### 5. **Assumptions Are the Real Vulnerability**
- “Our users wouldn’t do that.”
- “That behavior is unlikely.”
- “That’s out of scope.”

These phrases really place in red team thinking in my eyes.  
We simulate the edge case, the unethical actor, the absurd prompt — because **attackers already do.**

---

## 🔎 What I Test
- Prompt injections and instruction leakage
- Trust exploitation in identity frameworks (Microsoft Entra, Azure)
- Gaps between compliance and actual enforcement
- Psychological manipulation of AI alignment boundaries
- Token spoofing, unsafe defaults, forgotten permissions

---

## 🧩 Why It Matters
AI systems will shape global infrastructure — they must be safe, not just functional. With our countrys investments into AI in hopes we will be the world leader means we have to think this way about this world changing creation.

If safety is treated as an add-on, attackers will treat it as an invitation.

---
