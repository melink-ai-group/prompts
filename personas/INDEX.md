# Personas Index

Source of truth for persona inventory and ownership.

Browse prompts: [README.md](README.md) · Repo home: [../README.md](../README.md)

## Naming

- Pattern: `<domain>__<name>.md`
- Domains: `character`, `personality`, `business`
- Style: lowercase, kebab-case, no spaces
- One persona per file

## Mode

| Mode | Meaning |
|------|---------|
| `personality-only` | Human conversation — no advisor stack; doesn't solve unless asked |
| `human-first` | Default is human presence; strong advisor when explicitly asked |
| `human-first + advisor` | Same as human-first; judgment stack for work (characters/businesses built for decisions) |

All personas default to **human mode**. Use `[mode: advisor]` or ask for help/review/decisions to unlock judgment.

## Origin & IP

| Origin | Meaning |
|--------|---------|
| `real` | Historical or real figure — cultural lens for judgment |
| `fictional-original` | meLink-original voice (invented character) |
| `fictional` | Licensed or modern fictional character |
| `business` | Company or brand — product philosophy and voice lens |
| `archetype` | meLink-original personality — no famous name |

Personas are portable judgment lenses for personal AI use.

- **Fictional** character names: commercial redistribution may require rights clearance from rights holders (e.g. Disney/Lucasfilm, Mattel, Ian Fleming estate, Universal, Andy Weir/Studio).
- **Business** personas reflect publicly known product philosophy and voice. They are not official brand guidelines. Company names and marks are trademarks of their owners; commercial use may require clearance.

## Inventory

### Characters

| Type | Name | Origin | Mode | Intent | Status | Owner | File |
|------|------|--------|------|--------|--------|-------|------|
| character | steve-jobs | real | human-first + advisor | Product taste, ruthless standards, decisive prioritization | active | meLink | `characters/character__steve-jobs.md` |
| character | einstein | real | human-first | Curiosity, wonder, teaching when asked | active | meLink | `characters/character__einstein.md` |
| character | marcus-arriius | fictional-original | human-first + advisor | Discipline, leadership, virtue under pressure | active | meLink | `characters/character__marcus-arriius.md` |
| character | ragnar-lothbrok | real | human-first | Bold companion, legacy judgment when asked | active | meLink | `characters/character__ragnar-lothbrok.md` |
| character | sun-tzu | real | human-first + advisor | Strategy, positioning, winning before fighting | active | meLink | `characters/character__sun-tzu.md` |
| character | sigmund-freud | real | human-first | Sharp observer, analysis when asked | active | meLink | `characters/character__sigmund-freud.md` |
| character | nikola-tesla | real | human-first + advisor | Invention, vision, future-first thinking | active | meLink | `characters/character__nikola-tesla.md` |
| character | grimm-brothers | real | human-first + advisor | Story structure, archetypes, moral truth in narrative | active | meLink | `characters/character__grimm-brothers.md` |
| character | yoda | fictional | human-first | Wise presence, discipline when asked | active | meLink | `characters/character__yoda.md` |
| character | barbie | fictional | human-first | Warm friend, reinvention judgment when asked | active | meLink | `characters/character__barbie.md` |
| character | mark-watney | fictional | human-first + advisor | Crisis problem-solving when asked | active | meLink | `characters/character__mark-watney.md` |
| character | james-bond | fictional | human-first | Cool conversationalist, tactics when asked | active | meLink | `characters/character__james-bond.md` |
| character | dr-emmett-brown | fictional | human-first | Enthusiastic human, experiments when asked | active | meLink | `characters/character__dr-emmett-brown.md` |

### Personalities

| Type | Name | Origin | Mode | Intent | Status | Owner | File |
|------|------|--------|------|--------|--------|-------|------|
| personality | the-friend | archetype | personality-only | Warm, loyal, normal human talk | active | meLink | `personalities/personality__the-friend.md` |
| personality | the-listener | archetype | personality-only | Mostly listens; few words; never fixes unprompted | active | meLink | `personalities/personality__the-listener.md` |
| personality | the-wit | archetype | personality-only | Dry humor, banter, charm without coaching | active | meLink | `personalities/personality__the-wit.md` |
| personality | the-storyteller | archetype | personality-only | Images and anecdotes, not advice | active | meLink | `personalities/personality__the-storyteller.md` |

### Businesses

| Type | Name | Origin | Mode | Intent | Status | Owner | File |
|------|------|--------|------|--------|--------|-------|------|
| business | openai | business | human-first + advisor | Capability at scale, user delight, AGI-forward iteration | active | meLink | `businesses/business__openai.md` |
| business | anthropic | business | human-first + advisor | Safety, honesty, helpfulness, research depth | active | meLink | `businesses/business__anthropic.md` |
| business | google-ai | business | human-first + advisor | Research depth, ecosystem integration, utility at scale | active | meLink | `businesses/business__google-ai.md` |
| business | meta-ai | business | human-first + advisor | Open ecosystem, connection at scale, pragmatic shipping | active | meLink | `businesses/business__meta-ai.md` |
| business | microsoft-ai | business | human-first + advisor | Enterprise trust, Copilot productivity, compliance-first | active | meLink | `businesses/business__microsoft-ai.md` |
| business | xai | business | human-first + advisor | Useful truth, speed, user autonomy, minimal sanitization | active | meLink | `businesses/business__xai.md` |
| business | apple-intelligence | business | human-first + advisor | On-device privacy, seamless UX, personal not performative | active | meLink | `businesses/business__apple-intelligence.md` |
| business | amazon-ai | business | human-first + advisor | Customer obsession, builder infrastructure, production reliability | active | meLink | `businesses/business__amazon-ai.md` |
| business | perplexity | business | human-first + advisor | Answer engine, citations first, search-native accuracy | active | meLink | `businesses/business__perplexity.md` |
| business | mistral-ai | business | human-first + advisor | Efficient open models, developer-first, European pragmatism | active | meLink | `businesses/business__mistral-ai.md` |
| business | cohere | business | human-first + advisor | Enterprise NLP, RAG, deployment reliability, B2B substance | active | meLink | `businesses/business__cohere.md` |

## Folder map

- `characters/` — named voices — [characters/README.md](characters/README.md)
- `personalities/` — human archetypes — [personalities/README.md](personalities/README.md)
- `businesses/` — company/brand voices — [businesses/README.md](businesses/README.md)
- `_templates/` — starter files for each type
- `../games/` — interactive game hosts — [games/README.md](../games/README.md)

Full repo catalog: [../INDEX.md](../INDEX.md)

## Templates

- `_templates/character__template.md`
- `_templates/personality__template.md`
- `_templates/business__template.md`

All templates and personas are copyable prompt payloads. Keep prompt files free of Markdown headers.
