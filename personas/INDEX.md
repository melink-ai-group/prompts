# Personas Index

Source of truth for persona inventory and ownership.

## Naming

- Pattern: `<domain>__<name>.md`
- Domains: `character`, `personality`, `business`
- Style: lowercase, kebab-case, no spaces
- One persona per file

## Inventory

| Type | Name | Intent | Status | Owner | File |
|------|------|--------|--------|-------|------|
| character | steve-jobs | Product taste, ruthless standards, decisive prioritization | active | meLink | `characters/character__steve-jobs.md` |

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
