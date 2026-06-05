# Personas · How to Guide

Part of [meLink](../README.md#the-movement) — linking the world of AI to **you**. This doc covers what personas are and how to apply them.

---

## What personas are

**Personas** are the first link in the meLink chain.

Not costumes. **Human presence first** — a way of seeing, speaking, and being in conversation. Judgment and deliverables come **only when you ask**.

A persona encodes what usually lives only in someone's head:

- **How they see** — beliefs, standards, what they refuse to compromise on  
- **How they speak** — rhythm, directness, what they name out loud  
- **How they show up** — react, listen, banter, stay human — not fix unprompted  
- **How they decide** — when you explicitly want judgment, feedback, or output  

That is why a persona is more than a tone-of-voice doc. Paste it into a chat and the model inherits a person — not a helper bot performing wisdom. Characters and businesses can go full advisor when you ask. Personalities in `personalities/` stay human by default.

Each persona is a plain `.md` file (e.g. `characters/character__steve-jobs.md`). One file, one voice. You keep it. You can rename when needed. You pass it to a teammate and they get the same mind in their thread, not a paraphrase of yours.

When the link holds, something shifts: the machine stops sounding like support software and starts talking like someone you'd actually want in the room.

### Human mode vs advisor mode

| Mode | When | What you get |
|------|------|--------------|
| **Human** (default) | Venting, small talk, thinking out loud, "rough day" | Presence, reaction, banter — **no fixing** |
| **Advisor** | "Help me decide", "review this", "what should I", `[mode: advisor]` | Full judgment stack, deliverables, standards |

Every persona includes `[mode: human]` and `[mode: advisor]` modifiers. Say *"give me your honest take"* or *"review this"* to unlock advisor mode without pasting again.

---

## How to use one

The idea is simple. The steps below are how you apply it today — in any chat UI, without waiting for a perfect setup.

### Quick start (recommended)

Works in ChatGPT, Claude, Gemini, Cursor, and the rest.

| Step | What to do |
|------|------------|
| 1 | Open a `.md` persona and copy all (`Cmd/Ctrl+A`) |
| 2 | **Paste as your first message** in a **new** chat |
| 3 | Send it, then ask your real question in the next message |

Example:

1. *First message:* entire contents of `characters/character__steve-jobs.md`  
2. *Second message:* “Review this landing page copy for clarity.”

Personas can drift in long threads. Start a new chat to reset the link.

### Advanced — persistent instructions

Paste the persona once into a **system / custom instructions** slot so every message in that chat (or project) inherits it. Better for long sessions; setup varies by platform.

| Step | What to do |
|------|------------|
| 1 | Copy the full `.md` file |
| 2 | Paste into the platform’s instructions field (table below) |
| 3 | Start a **new** chat — don’t mix with old context |
| 4 | Ask your task in the user message only — don’t repeat the persona |

Keep one block of text. Don’t split across “who you are” / “how to respond” unless the UI forces it.

#### Where to paste

| Platform | Where | Notes |
|----------|--------|--------|
| **Claude** | Project → **Custom Instructions**, or **Settings → Custom instructions** | Long personas; strong adherence |
| **Cursor** | **Rules for AI** (project) or **User Rules** (global) | Persona + codebase context |
| **Gemini** | **Gem** instructions | One Gem per persona |
| **API** | `system` (or equivalent) message | No UI caps |
| **ChatGPT** | **Custom instructions** or **Custom GPT → Instructions** | **Least flexible** — see below |

#### ChatGPT (least flexible for Advanced)

- Global custom instructions: two short boxes, easy to truncate long personas.  
- **Workaround:** Custom GPT with full persona in **Instructions**; only chat inside that GPT.

#### Platform flexibility

When you use Advanced mode, how well the persona sticks depends on where you paste it. Ranked by control over the full text and consistency across a session:

1. **API** — full `system` text, per request  
2. **Claude** — Projects / custom instructions  
3. **Cursor** — project or user rules  
4. **Gemini** — Gems  
5. **ChatGPT** — short slots, global bleed, drifts easiest  

#### Tips

- Persona = **how** it behaves; your message = **what** to do.  
- If it breaks character: *“Stay in persona. No disclaimers.”*  
- If it coaches or fixes unprompted: *“Stay human. Don't fix unless I ask.”* or append `[mode: human]`.
- If you want full judgment: *“Give me your honest take”* or append `[mode: advisor]`.
- If it rambles: *“Talk less.”* or append `[tone: brief]`.
- For shared team voice in code: Cursor **project rules** + persona file in-repo.

| File | Role |
|------|------|
| `*.md` | Copy into chat (quick start) or into instructions (advanced) |
| [README.md](README.md) | Persona catalog — browse all prompts |
| [../README.md](../README.md) | meLink home — movement and quick start |
| [INDEX.md](INDEX.md) | Persona inventory — metadata, mode, naming |
| [../INDEX.md](../INDEX.md) | Full prompts catalog (all domains) |
| [../games/README.md](../games/README.md) | Game prompts |
| [../games/INDEX.md](../games/INDEX.md) | Game inventory |
