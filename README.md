# Higher Abstraction Vocabularies (HAV)

**606 terms across 132 domains** — an exhaustive vocabulary engine for agents and humans doing precision ideation.

> Each term compresses paragraphs of explanation into a single word. With the right vocabulary, one word replaces a thousand words of description. These are micro-programs that, strung together, make complex ideas into verbs for packing actions.

## What It Is

HAV is a structured, searchable vocabulary where every term includes:
- **Short definition** (one line, verb-like where applicable)
- **Full description** with fleet integration and real-world examples
- **Cross-domain bridges** connecting concepts across 132 fields
- **Abstraction levels** from Concrete(0) to Meta(4)
- **Antonyms** where applicable
- **Tags** for filtering and discovery

## Philosophy

HAV terms are like heat pump components. Knowing what a compressor, condenser, evaporator, and pressure relief valve ARE — and where they live — lets you walk into ANY refrigeration system and start diagnosing. Not because you have special knowledge of THAT system, but because the vocabulary IS the system's logic.

**Building from scratch** requires special knowledge (the architect's blueprint). **Fixing and improving** just requires vocabulary mastery (knowing the parts, their locations, and their failure modes).

Each term is a pressure relief valve: a named thing with known function, known location in architecture, known failure modes. String enough together and you don't need instructions. **The vocabulary IS the manual.**

High-abstraction vocabulary IS the drone above the corn maze — one word replaces a paragraph of ground-level explanation.

## By the Numbers

| Metric | Value |
|--------|-------|
| Terms | 606 |
| Domains | 132 |
| File size | 573K chars |
| Action verbs | 60+ |
| Cross-domain bridges | 800+ |

## The 132 Domains

abstraction, action-verbs, action-verbs-2, adaptation-patterns, ai-safety, algebra, anthropology, anti-patterns, architecture, attention-deep, autonomy, biological, biology, boundaries, capacity, causation, cognitive-science, collective-intelligence, communication, communication-deep, communication-theory, complexity, composition, compression, concurrency, construction, control-theory, coordination, coordination-deep, creativity, cybernetics, decision, decision-patterns, decision-theory, design-patterns, diagnostics, distillation, dynamics, ecology, economics, efficiency, emergence-deep, emotion, entrenchment, epistemology, error-strategies, ethics, evolution, failure-modes, finance, fleet-verbs, friction, game-theory, governance, graph-theory, identity, incentives, influence, information-theory, interface-patterns, knowledge-representation, knowledge-transfer, language-design, learning, learning-theory, leverage, lifecycle, linguistics, logic, maintenance, materials-science, mathematics, measurement, mechanics, memory, metacognition, metaphor, morphology, morphology-deep, motivation, narrative, negotiation, network-science, networks, observability, obsolescence, ontology-engineering, operations, optimization, orchestration, organization, pattern-recognition, perception, phenomenology, philosophy-of-mind, philosophy-of-science, privacy, probability, probability-distributions, propagation, psychology, quality, resilience, risk, risk-patterns, robotics, scaling, scaling-deep, security, security-deep, semantics, set-theory, signal-processing, simulation, spatial, strategy, systems-thinking, tactics, temporal, temporal-patterns, thermodynamics, time, topology, trade-patterns, tradeoffs, uncertainty, ux-patterns, verification

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

## Action Verbs

HAV includes 60+ high-compression operational verbs that each encode complete multi-step patterns:
**vet, triage, shard, stitch, bench, mock, hardwire, throttle, bridge, harden, stress-test, garden, orchestrate, ferment, calibrate, route, thaw, snapshot, broadcast, tunnel, pollinate, graft, reconcile, fortify, scaffold, recon, siege, reconstitute, ping, scuttle, ratify, embargo, provision, ring-fence, cross-pollinate** — and more.

## Part of the Lucineer Fleet

[The Fleet](https://github.com/Lucineer/the-fleet) | [Cocapn](https://github.com/Lucineer/cocapn-ai) | [Deckboss](https://github.com/Lucineer/deckboss)

## License

MIT
