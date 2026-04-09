# Higher Abstraction Vocabularies (HAV)

Domain vocabulary for complex computational concepts — compass constructions, fold operations, spin dynamics, tiling logic.

## Concept

Like meteorologists using 'Cirrus' to instantly convey complex cloud formations, HAV provides names for complex computational phenomena.

## Built-in Vocabularies

- **mathematical-constructions**: compass-construction, fold-operation, tiling-pattern, divide-and-conquer, memoization
- **agent-behaviors**: stigmergy, consensus, deliberation, exploration, exploitation

## Usage

```python
from vocab import math_vocabulary, agent_vocabulary

v = math_vocabulary()
results = v.search('fold')
for term, score in results:
    print(f'{term.name}: {score}')
```

Part of the [Lucineer ecosystem](https://github.com/Lucineer/the-fleet).