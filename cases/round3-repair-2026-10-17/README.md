# Targeted rule repair and independent first-answer checks — 2026-10-17

Extended the existing attribution rule to sender, channel, automation, payer, passive voice and cross-alternative leakage; the matrix now requests each field and its own source.

These are narrow rule/template repairs and synthetic supplied-material checks, not a comprehensive repository audit or live platform/product/marketing-effect test. Existing sources, licenses, prior cases and historical validation records are retained.

Each executor was a fresh configured `gpt-6.1-sol` agent given the current skill and root-authored synthetic input, without a reference answer or prior output. Another agent independently reviewed the frozen first submitted answer. Review command records identify retrospective reconstruction rather than native telemetry. Freeze hashes prove byte consistency with the recorded marker, not a trusted timestamp.

| Case | First-answer audit | Evidence | Independent review |
|---|---|---|---|
| attribution | PASS for this case only | [Input](attribution/brief.md), [first answer](attribution/raw-response.md), [tools](attribution/commands.json) | [Audit](attribution/review/audit.md) |

Each case records the exact loaded rule hashes, source/input, raw answer, tools, independent audit and export hashes. Public copies replace machine-local paths with placeholders and normalize remaining local path separators to portable slashes; original bytes remain local. No substantive answer content is changed. No private business input, real accounts, paid API calls or website changes were used.

Coverage limits: these cases do not establish automatic host-install compatibility, live rule compliance, product/source authenticity, image generation quality, publication readiness, reach, conversion or business effect. A PASS is the independent reviewer's judgment for the listed answer only; it is not a guarantee across future inputs.
