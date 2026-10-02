# Controlled Migration Framework

Status date: 2026-10-03

## Purpose

[PROPOSAL] Use this framework to move from the immutable v5.8 source toward a separately reviewed Rebuild 6.0 architecture. It establishes provenance, audit, conflict handling, and review gates. It does not authorize card rewrites, rule changes, or Canon promotion.

## Source boundary

[FACT] The source snapshot is SOURCE/v5.8/SYNAPSE & STEEL.md, designated immutable in SOURCE/v5.8/SOURCE_STATUS.md.

[FACT] The structural audit is 11_MIGRATION/V5_8_STRUCTURAL_AUDIT.md. Its findings describe the snapshot; they do not modify it.

[FACT] All derived work belongs outside SOURCE/v5.8. No migration output may overwrite the source snapshot.

## Status labels

Use these labels on audit and migration assertions:

- [FACT] Directly verified from an identified source.
- [CONFLICT] Sources or source blocks disagree, or a duplicated block leaves provenance ambiguous.
- [PROVISIONAL] A working interpretation awaiting validation.
- [PROPOSAL] A suggested target design that has not been approved as Canon.
- [UNKNOWN] The evidence does not settle the question.

Each [FACT] should name its source and, where useful, source heading/ID. Do not silently change a label. A proposal becomes Canon only through explicit owner review and approval recorded separately.

## Workflow and gates

1. [FACT] Verify the v5.8 byte-level digest and record the result.
2. [FACT] Maintain its immutable source designation and structural audit.
3. [PROPOSAL] Build a provenance map outside SOURCE/v5.8. Record source IDs, source labels, destination topic, status, and rationale; preserve duplicate occurrences as separate provenance entries.
4. [CONFLICT] Open a conflict record for each naming, terminology, duplicated-block, rules, or architecture disagreement. Quote or reference both sources; do not select a winner during inventory.
5. [PROVISIONAL] Draft target architecture separately in REBUILD_6.0. Clearly distinguish verified source facts from proposed target structure.
6. [PROPOSAL] Validate proposed rules and data structures through deterministic tests and human review, preserving version, seed, factions, decks, first player, ATS profile, difficulty, Warden configuration, results, and agency telemetry.
7. Require owner review and explicit approval before promoting any proposal to Canon or committing migration changes.

The project handoff sequence remains REQUEST → ANALYZE → PROPOSE → VALIDATE → REVIEW → APPROVE → COMMIT.

## Rebuild 6.0 branch controls

[FACT] Development is isolated on branch rebuild-6.0. Main is not modified, merged, or pushed by this workflow unless the owner separately authorizes such an action.

[FACT] The 288-card rebuild is not part of this setup step. No v5.8 card text is rewritten or promoted here.

## Initial unresolved records

- [CONFLICT] IDs 181–194 occur twice. IDs 181–193 are exact duplicate card blocks; ID 194 repeats identical card content in different surrounding context.
- [CONFLICT] The first faction is labeled New Carthage Enclave in its section heading and New Carthage in the range index.
- [CONFLICT] The handoff records a Corporate Hegemony OBSERVE / ACQUIRE doctrine reconciliation point.
- [CONFLICT] The handoff records differing character-value vocabularies between v5.8 and earlier architecture.
- [UNKNOWN] Owner decisions are required to resolve any of these conflicts. Inventory does not imply approval.
