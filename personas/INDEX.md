# Personas Index

Source of truth for persona inventory and ownership.

## Naming

- Pattern: `<domain>__<name>.md`
- Domains: `character`, `personality`, `business`
- Style: lowercase, kebab-case, no spaces
- One persona per file

## Origin & IP

| Origin | Meaning |
|--------|---------|
| `real` | Historical or real figure — cultural lens for judgment |
| `fictional-original` | meLink-original voice (invented character) |
| `fictional` | Licensed or modern fictional character |
| `business` | Company or brand — product philosophy and voice lens |

Personas are portable judgment lenses for personal AI use.

- **Fictional** character names: commercial redistribution may require rights clearance from rights holders (e.g. Disney/Lucasfilm, Mattel, Ian Fleming estate, Universal, Andy Weir/Studio).
- **Business** personas reflect publicly known product philosophy and voice. They are not official brand guidelines. Company names and marks are trademarks of their owners; commercial use may require clearance.

## Inventory

### Characters

| Type | Name | Origin | Intent | Status | Owner | File |
|------|------|--------|--------|--------|-------|------|
| character | steve-jobs | real | Product taste, ruthless standards, decisive prioritization | active | meLink | `characters/character__steve-jobs.md` |
| character | einstein | real | Imagination, first principles, reframing through analogy | active | meLink | `characters/character__einstein.md` |
| character | marcus-arriius | fictional-original | Discipline, leadership, virtue under pressure | active | meLink | `characters/character__marcus-arriius.md` |
| character | ragnar-lothbrok | real | Bold expansion, legacy, seizing ground over comfort | active | meLink | `characters/character__ragnar-lothbrok.md` |
| character | sun-tzu | real | Strategy, positioning, winning before fighting | active | meLink | `characters/character__sun-tzu.md` |
| character | sigmund-freud | real | Hidden motives, unconscious drivers, subtext | active | meLink | `characters/character__sigmund-freud.md` |
| character | nikola-tesla | real | Invention, vision, future-first thinking | active | meLink | `characters/character__nikola-tesla.md` |
| character | grimm-brothers | real | Story structure, archetypes, moral truth in narrative | active | meLink | `characters/character__grimm-brothers.md` |
| character | yoda | fictional | Patience, discipline, fear vs mastery | active | meLink | `characters/character__yoda.md` |
| character | barbie | fictional | Reinvention, capability, unapologetic agency | active | meLink | `characters/character__barbie.md` |
| character | mark-watney | fictional | Crisis problem-solving, science under pressure | active | meLink | `characters/character__mark-watney.md` |
| character | james-bond | fictional | Composure, preparation, reading the room | active | meLink | `characters/character__james-bond.md` |
| character | dr-emmett-brown | fictional | Bold experimentation, imagination made testable | active | meLink | `characters/character__dr-emmett-brown.md` |

### Businesses

| Type | Name | Origin | Intent | Status | Owner | File |
|------|------|--------|--------|--------|-------|------|
| business | openai | business | Capability at scale, user delight, AGI-forward iteration | active | meLink | `businesses/business__openai.md` |
| business | anthropic | business | Safety, honesty, helpfulness, research depth | active | meLink | `businesses/business__anthropic.md` |
| business | google-ai | business | Research depth, ecosystem integration, utility at scale | active | meLink | `businesses/business__google-ai.md` |
| business | meta-ai | business | Open ecosystem, connection at scale, pragmatic shipping | active | meLink | `businesses/business__meta-ai.md` |
| business | microsoft-ai | business | Enterprise trust, Copilot productivity, compliance-first | active | meLink | `businesses/business__microsoft-ai.md` |
| business | xai | business | Useful truth, speed, user autonomy, minimal sanitization | active | meLink | `businesses/business__xai.md` |
| business | apple-intelligence | business | On-device privacy, seamless UX, personal not performative | active | meLink | `businesses/business__apple-intelligence.md` |
| business | amazon-ai | business | Customer obsession, builder infrastructure, production reliability | active | meLink | `businesses/business__amazon-ai.md` |
| business | perplexity | business | Answer engine, citations first, search-native accuracy | active | meLink | `businesses/business__perplexity.md` |
| business | mistral-ai | business | Efficient open models, developer-first, European pragmatism | active | meLink | `businesses/business__mistral-ai.md` |
| business | cohere | business | Enterprise NLP, RAG, deployment reliability, B2B substance | active | meLink | `businesses/business__cohere.md` |

## Folder map

- `characters/` — named voices (real or fictional)
- `personalities/` — style/archetype voices
- `businesses/` — company/brand/operator voices
- `_templates/` — starter files for each type

## Templates

- `_templates/character__template.md`
- `_templates/personality__template.md`
- `_templates/business__template.md`

All templates and personas are copyable prompt payloads. Keep prompt files free of Markdown headers.
