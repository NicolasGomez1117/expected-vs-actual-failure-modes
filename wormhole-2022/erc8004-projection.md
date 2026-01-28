# ERC-8004 projection (structural lens)

Wormhole does not implement ERC-8004. ERC-8004 is used here only as a structural lens for organizing observable signals. No compliance or completeness is claimed.

## Projection map
| Observation in evidence | ERC-8004 concept (lens) | Status |
| --- | --- | --- |
| `events_file_present: true` | event surface exists | observed |
| `state_file_present: true` | state snapshot exists | observed |
| `terminal_state: unknown` | terminal status | unknown |
| `agent_ids_seen: unknown` | agents participating | unknown |
| `agent_id_mismatch: unknown` | agent consistency | unknown |
| `schema_versions_seen: unknown` | schema versioning | unknown |

## Information loss
- No actor intent, causal chain, or exploit details are carried forward.
- No address-level or transaction-level context is retained.
- No guarantee of completeness: this is a projection, not a reconstruction.
