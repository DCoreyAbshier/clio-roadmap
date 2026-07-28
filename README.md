# Clio Roadmap

Clio is an AI-assisted role-playing engine focused on coherent long-running worlds, recognizable characters, and consistent scenes.

This repository is Clio's public, high-level product roadmap. It intentionally excludes private source code, detailed architecture, internal acceptance criteria, security information, and deployment details.

> The roadmap describes intended direction, not promised release dates. Correctness, security, data integrity, or production reliability work may change the order.

## Current focus

| Position | Outcome | Status |
| --- | --- | --- |
| 1 | [Track significant objects and placement](https://github.com/DCoreyAbshier/clio-roadmap/issues/5) | **Next** |

## Recently delivered foundations

- [x] Reliable recovery for interrupted or lost generation responses
- [x] Stronger Location authority and continuity safeguards
- [x] Correct temporal inheritance when Scenes split
- [x] Geographic continuity protections
- [x] A bounded architecture for Character identity and multi-perspective Scenes
- [x] Typed, effective-dated Character Continuity and Scene State
- [x] Direct-generation access to richer Character state without additional model calls
- [x] A layered, versioned World schema registry with validation and typed references
- [x] Shared schema-driven Canon authoring and World extension support
- [x] Versioned, World-configurable Character Condition vocabularies and setting packs
- [x] Typed Character Condition lifecycle, historical projection, and viewpoint-safe diagnosis
- [x] Sparse, effective-dated Character Expression with resistances and weaknesses
- [x] Audit-first Character Expression rollout with player-agency protection
- [x] Campaign-scoped player-agency and viewpoint contracts across Scene types
- [x] Accessible intent-aware Play input and a player-only Status Effects surface

## Ordered roadmap

| Order | Public outcome | Phase | Status |
| ---: | --- | --- | --- |
| 1 | [Typed world-object schema registry](https://github.com/DCoreyAbshier/clio-roadmap/issues/1) | Shared foundations | **Delivered** |
| 2 | [Configurable Character Conditions](https://github.com/DCoreyAbshier/clio-roadmap/issues/2) | Character foundations | **Delivered** |
| 3 | [Stable Character Expression](https://github.com/DCoreyAbshier/clio-roadmap/issues/3) | Character foundations | **Delivered** |
| 4 | [Player agency and improved Play input](https://github.com/DCoreyAbshier/clio-roadmap/issues/4) | Character foundations | **Delivered** |
| 5 | [Significant objects and placement](https://github.com/DCoreyAbshier/clio-roadmap/issues/5) | Character foundations | **Next** |
| 6 | [Character development and progression](https://github.com/DCoreyAbshier/clio-roadmap/issues/6) | Character foundations | Planned |
| 7 | [Stronger transaction and effect handling](https://github.com/DCoreyAbshier/clio-roadmap/issues/7) | Causation and integrity | Planned |
| 8 | [Explicit dependency relationships](https://github.com/DCoreyAbshier/clio-roadmap/issues/8) | Causation and integrity | Planned |
| 9 | [Dependency-aware downstream updates](https://github.com/DCoreyAbshier/clio-roadmap/issues/9) | Causation and integrity | Planned |
| 10 | [Significant information and Character awareness](https://github.com/DCoreyAbshier/clio-roadmap/issues/10) | Knowledge and relationships | Planned |
| 11 | [Relationship state and social initiative](https://github.com/DCoreyAbshier/clio-roadmap/issues/11) | Knowledge and relationships | Planned |
| 12 | [Compound turns across Scenes](https://github.com/DCoreyAbshier/clio-roadmap/issues/12) | Scenes and simulation | Planned |
| 13 | [New Scenes when Locations are revisited](https://github.com/DCoreyAbshier/clio-roadmap/issues/13) | Scenes and simulation | Planned |
| 14 | [Bounded simulation checkpoints](https://github.com/DCoreyAbshier/clio-roadmap/issues/14) | Scenes and simulation | Planned |
| 15 | [Bounded multi-Character orchestration](https://github.com/DCoreyAbshier/clio-roadmap/issues/15) | Scenes and simulation | Planned |
| 16 | [Location spatial state and significant history](https://github.com/DCoreyAbshier/clio-roadmap/issues/16) | World presentation | Planned |
| 17 | [Persistent Location visual sets](https://github.com/DCoreyAbshier/clio-roadmap/issues/17) | World presentation | Planned |
| 18 | [Canon encyclopedia browser](https://github.com/DCoreyAbshier/clio-roadmap/issues/18) | Authoring and presentation | Planned |
| 19 | [Downloadable versioned import templates](https://github.com/DCoreyAbshier/clio-roadmap/issues/19) | Authoring and presentation | Planned |
| 20 | [Declarative presentation themes](https://github.com/DCoreyAbshier/clio-roadmap/issues/20) | Authoring and presentation | Planned |
| 21 | [Persistent World news experience](https://github.com/DCoreyAbshier/clio-roadmap/issues/21) | Authoring and presentation | Planned |
| 22 | [Secure internal runtime interface evaluation](https://github.com/DCoreyAbshier/clio-roadmap/issues/22) | Future integration | Deferred |
| 23 | [Event and faction simulation evaluation](https://github.com/DCoreyAbshier/clio-roadmap/issues/23) | Future simulation | Deferred |
| 24 | [Obsolete demo-content retirement](https://github.com/DCoreyAbshier/clio-roadmap/issues/24) | Maintenance | Opportunistic |

## How progress is tracked

- **Delivered** means the high-level public outcome has shipped and its roadmap issue is closed.
- **Active** means the outcome is currently being implemented.
- **Next** is the immediate follow-up after active work or the first ready item when no work is active.
- **Planned** work follows the displayed execution order.
- **Deferred** work has deliberate entry conditions that have not been met.
- **Opportunistic** maintenance is performed when a safe, natural opening appears.
- Issue titles and this dashboard are updated when execution order or status changes.

Browse and follow the individual [public roadmap issues](https://github.com/DCoreyAbshier/clio-roadmap/issues).

## Product principles behind the order

1. Protect correctness, authority, recoverability, and player agency first.
2. Build shared foundations before derived simulation or presentation layers.
3. Deliver the smallest useful vertical slice at each stage.
4. Preserve reliable existing paths while advanced behavior is proven incrementally.
5. Add optional integration or broader automation only after a concrete benefit is demonstrated.

_Last synchronized with Clio's private engineering roadmap: July 27, 2026._
