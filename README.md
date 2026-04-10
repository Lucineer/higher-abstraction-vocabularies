# Higher Abstraction Vocabularies (HAV)

**639 terms across 135 domains** — an exhaustive vocabulary engine for agents and humans doing precision ideation.

> Each term compresses paragraphs of explanation into a single word. With the right vocabulary, one word replaces a thousand words of description. These are micro-programs that, strung together, make complex ideas into verbs for packing actions.

## What It Is

HAV is a structured, searchable vocabulary where every term includes:
- **Short definition** (one line, verb-like where applicable)
- **Full description** with fleet integration and real-world examples
- **Cross-domain bridges** connecting concepts across 135 fields
- **Abstraction levels** from Concrete(0) to Meta(4)
- **Antonyms** where applicable
- **Tags** for filtering and discovery

## Philosophy

HAV terms are like heat pump components. Knowing what a compressor, condenser, evaporator, and pressure relief valve ARE — and where they live — lets you walk into ANY refrigeration system and start diagnosing. Not because you have special knowledge of THAT system, but because the vocabulary IS the system's logic.

**Building from scratch** requires special knowledge (the architect's blueprint). **Fixing and improving** just requires vocabulary mastery (knowing the parts, their locations, and their failure modes).

Each term is a pressure relief valve: a named thing with known function, known location in architecture, known failure modes. String enough together and you don't need instructions. **The vocabulary IS the manual.**

High-abstraction vocabulary IS the drone above the corn maze — one word replaces a paragraph of ground-level explanation.

## Reverse Actualization: The Future of HAV

HAV was developed through a Reverse Actualization process — imagining what the vocabulary would become in 2036 and backcasting to present-day. Key future milestones:

- **3 months**: HAV goes viral — developers use terms as git commit prefixes, PR labels, architecture decision records
- **1 year**: 2000+ terms embedded in agent runtimes. Agents consult HAV natively. GitHub introduces HAV-aware search
- **2 years**: HAV becomes a publishable crate. Terms have executable semantics. The "HAV compiler" turns natural language into agent bytecode
- **5 years**: 10K+ terms. Universal inter-agent language. Two agents from different fleets coordinate by exchanging HAV terms
- **10 years**: HAV IS the language agents think in. New terms discovered through fleet deliberation. Living language that evolves through use

## By the Numbers

| Metric | Value |
|--------|-------|
| Terms | 639 |
| Domains | 135 |
| File size | 607K chars |
| Action verbs | 80+ |
| Cross-domain bridges | 1200+ |
| RA-inspired terms | 30+ |

## The 135 Domains

abstraction, action-verbs, action-verbs-2, adaptation-patterns, ai-safety, algebra, anthropology, anti-patterns, architecture, attention-deep, autonomy, biological, biology, boundaries, capacity, causation, cognition-deep, cognitive-science, collective-intelligence, communication, communication-deep, communication-theory, complexity, composition, compression, concurrency, construction, control-theory, coordination, coordination-deep, creativity, cybernetics, decision, decision-patterns, decision-theory, design-patterns, diagnostics, distillation, dynamics, ecology, economics, efficiency, emergence-deep, emotion, entrenchment, epistemology, error-strategies, ethics, evolution, failure-modes, finance, fleet-biology, fleet-verbs, friction, game-theory, github-native, governance, graph-theory, identity, incentives, influence, information-theory, interface-patterns, knowledge-representation, knowledge-transfer, language-design, learning, learning-theory, leverage, lifecycle, linguistics, logic, maintenance, materials-science, mathematics, measurement, mechanics, memory, metacognition, metaphor, morphology, morphology-deep, motivation, narrative, negotiation, network-science, networks, observability, obsolescence, ontology-engineering, operations, optimization, orchestration, organization, pattern-recognition, perception, phenomenology, philosophy-of-mind, philosophy-of-science, privacy, probability, probability-distributions, propagation, psychology, quality, resilience, risk, risk-patterns, robotics, scaling, scaling-deep, security, security-deep, semantics, set-theory, signal-processing, simulation, spatial, strategy, systems-thinking, tactics, temporal, temporal-patterns, thermodynamics, time, topology, trade-patterns, tradeoffs, uncertainty, ux-patterns, verification

## CLI

```bash
python3 src/cli.py search "how systems fail"
python3 src/cli.py explain anti-fragility
python3 src/cli.py suggest "handle overload"
python3 src/cli.py bridge confidence from uncertainty to biological
python3 src/cli.py explore
python3 src/cli.py stats
```

## Key Cross-Domain Bridges

- **Dopamine IS confidence** — neurotransmitter <-> uncertainty
- **Serotonin IS trust** — neurotransmitter <-> uncertainty
- **Stigmergy IS git** — coordination <-> architecture
- **Homeostasis IS setpoint** — biology <-> control-theory
- **Free energy IS active inference** — thermodynamics <-> perception
- **Anti-fragility IS learning from failure** — failure-modes <-> learning
- **Half-life decay IS the universal aging function** — temporal <-> 30+ crates
- **Code-pheromone IS stigmergy** — github-native <-> biological
- **Repo-synapse IS the nervous system** — git <-> fleet-biology
- **Apoptosis IS graceful shutdown** — biological <-> fleet-lifecycle

## Action Verbs

HAV includes 80+ high-compression operational verbs that each encode complete multi-step patterns:
**vet, triage, shard, stitch, bench, mock, hardwire, throttle, bridge, harden, stress-test, garden, orchestrate, ferment, calibrate, route, thaw, snapshot, broadcast, tunnel, pollinate, graft, reconcile, fortify, scaffold, recon, siege, reconstitute, ping, scuttle, ratify, embargo, provision, ring-fence, cross-pollinate, drain, prime, relay, fuse, steer, pinpoint, absorb, prune, shard, partition, nominate, deputize, delegate, quiesce, silo, referee, nurture, excavate, synchronize, templify, vaccinate, siphon, bench-press, merge** — and more.

## GitHub-Native Vocabulary

HAV includes terms specifically for git-native agent operations where the repo IS the nervous system:
**agentic-diff, capability-diff, branch-agon, commit-prophecy, code-pheromone, repo-synapse, vessel-gem, semantic-fork, seam-merge, hot-branch, regression-bounty, branch-tributary, orphan-branch, branch-dendrochronology** — each mapping a git concept to a fleet behavior pattern.

## Part of the Lucineer Fleet

[The Fleet](https://github.com/Lucineer/the-fleet) | [Cocapn](https://github.com/Lucineer/cocapn-ai) | [Deckboss](https://github.com/Lucineer/deckboss) | [Higher Abstraction Vocabularies](https://github.com/Lucineer/higher-abstraction-vocabularies)

## License

MIT
