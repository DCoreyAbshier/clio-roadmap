# Clio Roadmap

Clio is an AI-assisted role-playing engine focused on coherent long-running worlds, recognizable characters, and consistent scenes.

This repository is Clio's public, high-level product roadmap. It intentionally excludes private source code, detailed architecture, internal acceptance criteria, security information, and deployment details.

> The roadmap describes intended direction, not promised release dates. Correctness, security, data integrity, owner-directed cleanup, or production reliability work may change the order.

## Current focus

**Narrative Fidelity Guard** is now Clio's active critical outcome. The immediate next slice defines provider-independent fidelity contracts and a paired adversarial corpus before any runtime blocking behavior is considered. Other planned and tooling-gated work remains ordered behind this program.

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
- [x] Application-owned downloadable versioned import templates and starter bundle
- [x] A single native Play composer with compact inline intent feedback
- [x] Layered Location baseline, current Spatial State, significant-transition history, and Scene-context integration
- [x] Persistent Location visual sets with Canon management and subordinate Play orientation
- [x] Readable Canon object references and complete eligible Character-tag Scene inclusion in Play
- [x] Adaptive Context-depth and response-scope planning with World-level Auto and fixed preferences
- [x] Retained, continuity-scoped World media ticker and article drill-down
- [x] One authoritative bounded Scene-turn path with optional zero-to-two Character workers
- [x] Conversation-first authoritative fast-forward with explicit Location and cast targeting
- [x] Supported declarative Play themes with safe preference resolution and Location-backdrop integration
- [x] Reversible versioned adaptive-runtime defaults for newly created Worlds

## Ordered roadmap

| Order | Public outcome | Phase | Status |
| ---: | --- | --- | --- |
| 1 | [Narrative Fidelity Guard](https://github.com/DCoreyAbshier/clio-roadmap/issues/29) | Narrative integrity | **Active** |
| 2 | [Typed world-object schema registry](https://github.com/DCoreyAbshier/clio-roadmap/issues/1) | Shared foundations | **Delivered** |
| 3 | [Configurable Character Conditions](https://github.com/DCoreyAbshier/clio-roadmap/issues/2) | Character foundations | **Delivered** |
| 4 | [Stable Character Expression](https://github.com/DCoreyAbshier/clio-roadmap/issues/3) | Character foundations | **Delivered** |
| 5 | [Player agency and improved Play input](https://github.com/DCoreyAbshier/clio-roadmap/issues/4) | Character foundations | **Delivered** |
| 6 | [Significant objects and placement](https://github.com/DCoreyAbshier/clio-roadmap/issues/5) | Character foundations | **Delivered** |
| 7 | [Character development and progression](https://github.com/DCoreyAbshier/clio-roadmap/issues/6) | Character foundations | **Delivered** |
| 8 | [Stronger transaction and effect handling](https://github.com/DCoreyAbshier/clio-roadmap/issues/7) | Causation and integrity | **Delivered** |
| 9 | [Explicit dependency relationships](https://github.com/DCoreyAbshier/clio-roadmap/issues/8) | Causation and integrity | **Delivered** |
| 10 | [Dependency-aware downstream updates](https://github.com/DCoreyAbshier/clio-roadmap/issues/9) | Causation and integrity | **Delivered** |
| 11 | [Canon encyclopedia browser](https://github.com/DCoreyAbshier/clio-roadmap/issues/18) | Authoring and presentation | **Delivered** |
| 12 | [Significant information and Character awareness](https://github.com/DCoreyAbshier/clio-roadmap/issues/10) | Knowledge and relationships | **Delivered** |
| 13 | [Relationship state and social initiative](https://github.com/DCoreyAbshier/clio-roadmap/issues/11) | Knowledge and relationships | **Delivered** |
| 14 | [Compound turns across Scenes](https://github.com/DCoreyAbshier/clio-roadmap/issues/12) | Scenes and simulation | **Delivered** |
| 15 | [New Scenes when Locations are revisited](https://github.com/DCoreyAbshier/clio-roadmap/issues/13) | Scenes and simulation | **Delivered** |
| 16 | [Bounded simulation checkpoints](https://github.com/DCoreyAbshier/clio-roadmap/issues/14) | Scenes and simulation | **Delivered** |
| 17 | [Bounded multi-Character orchestration](https://github.com/DCoreyAbshier/clio-roadmap/issues/15) | Scenes and simulation | **Delivered** |
| 18 | [Downloadable versioned import templates](https://github.com/DCoreyAbshier/clio-roadmap/issues/19) | Authoring and presentation | **Delivered** |
| 19 | [Location spatial state and significant history](https://github.com/DCoreyAbshier/clio-roadmap/issues/16) | World presentation | **Delivered** |
| 20 | [Persistent Location visual sets](https://github.com/DCoreyAbshier/clio-roadmap/issues/17) | World presentation | **Delivered** |
| 21 | [Canon object and tag-group references in Play](https://github.com/DCoreyAbshier/clio-roadmap/issues/25) | Play and authoring | **Delivered** |
| 22 | [Adaptive generation planning](https://github.com/DCoreyAbshier/clio-roadmap/issues/26) | Scenes and generation | **Delivered** |
| 23 | [Persistent World news experience](https://github.com/DCoreyAbshier/clio-roadmap/issues/21) | Authoring and presentation | **Delivered** |
| 24 | [Conversation-first authoritative fast-forward](https://github.com/DCoreyAbshier/clio-roadmap/issues/28) | Scenes and continuity | **Delivered** |
| 25 | [Declarative presentation themes](https://github.com/DCoreyAbshier/clio-roadmap/issues/20) | Authoring and presentation | Foundation delivered; expansion planned |
| 26 | [Source-backed reference-world research in Play](https://github.com/DCoreyAbshier/clio-roadmap/issues/27) | Reference-world context | Planned |
| 27 | [Secure internal runtime interface evaluation](https://github.com/DCoreyAbshier/clio-roadmap/issues/22) | Future integration | Deferred |
| 28 | [Event and faction simulation evaluation](https://github.com/DCoreyAbshier/clio-roadmap/issues/23) | Future simulation | Deferred |
| 29 | [Obsolete demo-content retirement](https://github.com/DCoreyAbshier/clio-roadmap/issues/24) | Maintenance | Opportunistic |

## How progress is tracked

- **Delivered** means the high-level public outcome has shipped and its roadmap issue is closed.
- **Active** means the outcome is currently being implemented.
- **Foundation delivered; expansion planned** means the first supported product slice has shipped while later bounded phases remain open.
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

_Last synchronized with Clio's private engineering roadmap: August 2, 2026._
