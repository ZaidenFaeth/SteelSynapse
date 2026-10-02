# v5.8 Structural Audit

Audit date: 2026-10-03

## Scope and method

[FACT] This audit examines SOURCE/v5.8/SYNAPSE & STEEL.md and records structure and provenance. It does not edit, normalize, deduplicate, reinterpret, or promote source content. Size and SHA-256 were measured on the original file bytes; heading analysis used a read-only parser over the numbered bold card headings.

[FACT] File size: 149,336 bytes (6,135 lines).

[FACT] SHA-256: 1c0b5b4af594a32fab1c4bc76e64444e748c62364a2286b03a381480c13a24bc.

[FACT] The SHA-256 exactly matches the supplied expected digest.

## Numbered headings and ID coverage

[FACT] Numbered card-heading occurrences: 258.

[FACT] Unique numbered IDs: 244, covering 001 through 244.

[CONFLICT] IDs 181 through 194 each occur twice.

[FACT] No IDs are missing from the 001–244 range.

## Duplicate-block comparison

[FACT] For IDs 181–193, each occurrence’s card block, measured from its numbered heading to the next numbered card heading, is an exact match to its duplicate. These are 13 exact duplicate ID pairs.

[CONFLICT] ID 194 appears twice. Its card content is identical, verified by comparing the text span of each card independently. The surrounding section context differs, so the complete surrounding blocks are not identical.

[UNKNOWN] The file does not state why these duplicate blocks exist or which context should govern. This audit does not infer a correction or preferred copy.

## Faction and card-range structure

[FACT] Seven existing faction pools are represented, each covering 24 IDs:

- 001–024 — New Carthage
- 025–048 — Omega Foundry
- 049–072 — Waste-Walkers
- 073–096 — Ascetic Monks
- 097–120 — Corporate Hegemony
- 121–144 — Scrap-Metal Zealots
- 145–168 — Void-Walkers

[CONFLICT] The opening section labels faction I “New Carthage Enclave,” while the range index calls it “New Carthage.” The label variation is recorded without selecting one.

[FACT] The remaining indexed blocks are 169–180 Sunder Ecosystem; 181–194 Cores; 195–208 Directives; 209–220 Neutral Infrastructure; and 221–244 Ultimate Threats.

## Requested system blocks

[FACT] Cores: 181–194, 14 unique IDs, each duplicated in the source.

[FACT] Directives: 195–208, 14 IDs.

[FACT] Neutral Infrastructure: 209–220, 12 IDs. Sector-related language also appears in the source; its range index uses the label Neutral Infrastructure.

[FACT] Ultimate Threats: 221–244, 24 IDs.

## Structural anomalies and apparent conflicts

[CONFLICT] The Cores range is duplicated. IDs 181–193 are exact duplicate card blocks; ID 194’s card content matches while its surrounding context differs.

[CONFLICT] The first faction has a label variation: New Carthage Enclave / New Carthage.

[CONFLICT] HANDOFF/CURRENT_STATE.md records two unresolved cross-document issues: v5.8 Corporate Hegemony’s OBSERVE emphasis versus the proposed ACQUIRE doctrine, and v5.8 character-value vocabulary versus earlier architecture vocabulary. They remain review items and are not reconciled here.

[UNKNOWN] Whether the duplicated blocks and label variation are transcription artifacts, intentional historical variants, or a mixture is not established by structural evidence alone.

[UNKNOWN] This is a structural/provenance audit, not a complete card-by-card rules consistency, balance, or playability review. No additional semantic contradiction is asserted without separate evidence-based analysis.

## Historical-source handling

[FACT] The entire v5.8 file—including repeated blocks, historical wording, section names, and context—is retained as source material.

[PROPOSAL] Record any future mapping or interpretation in separate provenance-linked documents after review. Never change the source snapshot or treat Rebuild 6.0 proposals as corrections to it.
