# META_Codex 2.0 Specification

## 1. File naming
- Format: `META_Codex_YYYYMMDD_HHMM.jsonld`
- Example: `META_Codex_20260115_1422.jsonld`

## 2. Required fields
Every file must contain:
- `name`: short title of the trajectory
- `description`: what this trajectory represents
- `ascalonPurity`: float ≥ 0.7 (quality of sense)
- `coherenceIndex`: float 0–1 (spatial-temporal coherence)
- `energyLevel`: float 0–10 (intensity of the field)
- `epistemicTensionSeries`: list of Δ(t) values
- `meaningEnergySeries`: list of Eₛ(t) values
- `witnessState`: "ACTIVE", "SILENT", or "DRIFT"
- `generatedBy`: e.g., "LifeNode 2.6 (Zero-Build)"
- `timestamp`: ISO 8601
- `license`: "CC-BY-SA 4.0"

## 3. Machine-readable JSON-LD context
See example in [`template/META_Codex_template.jsonld`](template/META_Codex_template.jsonld)
