# Clio Roadmap

Clio is an AI-assisted role-playing engine focused on coherent long-running worlds, recognizable characters, and consistent scenes.

This repository is Clio's public, high-level product roadmap. It intentionally excludes private source code, detailed architecture, internal acceptance criteria, security information, and deployment details.

> The roadmap describes intended direction, not promised release dates. Correctness, security, data integrity, owner-directed cleanup, or production reliability work may change the order.

## Current focus

| Position | Outcome | Status |
| --- | --- | --- |
| 1 | [Add bounded multi-Character orchestration](https://github.com/DCoreyAbshier/clio-roadmap/issues/15) | **Next** |

The next outcome will coordinate small casts through finite Character proposals, audience-safe Scene beats, explicit model-call and token budgets, and one authoritative final Play completion while preserving direct generation as the default fallback.

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
- [x] Safe legacy fallback when a Scene has no authoritative story position
- [x] Campaign-scoped player-agency and viewpoint contracts across Scene types
- [x] Accessible intent-aware Play input and a player-only Status Effects surface
- [x] Significant-object identity, ownership, condition, and effective-dated placement history
- [x] Effective-dated Pursuits with separate desire and obligation facets
- [x] Continuity-scoped Achievements, Credentials, and coordinated Character-development outcomes
- [x] Safe manual Canon transaction and typed-effect handling
- [x] Accepted dependency paths with bounded traversal and explicit coverage
- [x] Bounded downstream consequences, conflicts, retry, supersession, and reversion
- [x] A unified Canon encyclopedia with impact-confirmed lifecycle supersession for supported objects
- [x] Effective-dated Event dissemination with Character awareness and audience-specific reputation
- [x] Directional relationship state with qualitative Activation Pressure and social initiative
- [x] Bounded compound turns with isolated per-Scene context and atomic persistence
- [x] Distinct Scenes for later visits while reusing authoritative Location identity
- [x] Deterministic bounded simulation checkpoints with audience-scoped escalation

## Ordered roadmap

| Order | Public outcome | Phase | Status |
| ---: | --- | --- | --- |
| 1 | [Typed world-object schema registry](https://github.com/DCoreyAbshier/clio-roadmap/issues/1) | Shared foundations | **Delivered** |
| 2 | [Configurable Character Conditions](https://github.com/DCoreyAbshier/clio-roadmap/issues/2) | Character foundations | **Delivered** |
| 3 | [Stable Character Expression](https://github.com/DCoreyAbshier/clio-roadmap/issues/3) | Character foundations | **Delivered** |
| 4 | [Player agency and improved Play input](https://github.com/DCoreyAbshier/clio-roadmap/issues/4) | Character foundations | **Delivered** |
| 5 | [Significant objects and placement](https://github.com/DCoreyAbshier/clio-roadmap/issues/5) | Character foundations | **Delivered** |
| 6 | [Character development and progression](https://github.com/DCoreyAbshier/clio-roadmap/issues/6) | Character foundations | **Delivered** |
| 7 | [Stronger transaction and effect handling](https://github.com/DCoreyAbshier/clio-roadmap/issues/7) | Causation and integrity | **Delivered** |
| 8 | [Explicit dependency relationships](https://github.com/DCoreyAbshier/clio-roadmap/issues/8) | Causation and integrity | **Delivered** |
| 9 | [Dependency-aware downstream updates](https://github.com/DCoreyAbshier/clio-roadmap/issues/9) | Causation and integrity | **Delivered** |
| 10 | [Canon encyclopedia browser](https://github.com/DCoreyAbshier/clio-roadmap/issues/18) | Authoring and presentation | **Delivered** |
| 11 | [Significant information and Character awareness](https://github.com/DCoreyAbshier/clio-roadmap/issues/10) | Knowledge and relationships | **Delivered** |
| 12 | [Relationship state and social initiative](https://github.com/DCoreyAbshier/clio-roadmap/issues/11) | Knowledge and relationships | **Delivered** |
| 13 | [Compound turns across Scenes](https://github.com/DCoreyAbshier/clio-roadmap/issues/12) | Scenes and simulation | **Delivered** |
| 14 | [New Scenes when Locations are revisited](https://github.com/DCoreyAbshier/clio-roadmap/issues/13) | Scenes and simulation | **Delivered** |
| 15 | [Bounded simulation checkpoints](https://github.com/DCoreyAbshier/clio-roadmap/issues/14) | Scenes and simulation | **Delivered** |
| 16 | [Bounded multi-Character orchestration](https://github.com/DCoreyAbshier/clio-roadmap/issues/15) | Scenes and simulation | **Next** |
| 17 | [Downloadable versioned import templates](https://github.com/DCoreyAbshier/clio-roadmap/issues/19) | Authoring and presentation | Planned |
| 18 | [Location spatial state and significant history](https://github.com/DCoreyAbshier/clio-roadmap/issues/16) | World presentation | Planned |
| 19 | [Persistent Location visual sets](https://github.com/DCoreyAbshier/clio-roadmap/issues/17) | World presentation | Planned |
| 20 | [Declarative presentation themes](https://github.com/DCoreyAbshier/clio-roadmap/issues/20) | Authoring and presentation | Planned |
| 21 | [Persistent World news experience](https://github.com/DCoreyAbshier/clio-roadmap/issues/21) | Authoring and presentation | Planned |
| 22 | [Secure internal runtime interface evaluation](https://github.com/DCoreyAbshier/clio-roadmap/issues/22) | Future integration | Deferred |
| 23 | [Event and faction simulation evaluation](https://github.com/DCoreyAbshier/clio-roadmap/issues/23) | Future simulation | Deferred |
| 24 | [Obsolete demo-content retirement](https://github.com/DCoreyAbshier/clio-roadmap/issues/24) | Maintenance | Opportunistic |

## How progress is tracked

- **Delivered** means the high-level public outcome has shipped and its roadmap issue is closed.
- **Active** means the outcome is currently being implemented.
- **Next** is the immediate follow-up after active work or the first ready public outcome when no public feature is active.
- **Planned** work follows the displayed execution order unless correctness or a discovered dependency requires a documented change.
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

_Last synchronized with Clio's private engineering roadmap: July 29, 2026._
