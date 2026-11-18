
# NOVA-001: Catastrophic Forgetting

## Objective
Investigate what happens when an AI learns new information after learning an earlier task.

## Experiment
The neural network learned handwritten digits 0–4, then digits 5–9.

## Results

| Measurement | Accuracy |
|---|---:|
| Initial knowledge | 99.56% |
| Old knowledge after second lesson | 0.00% |
| New knowledge after second lesson | 99.11% |

## Conclusion
The experiment demonstrated catastrophic forgetting in our neural network.

## Next step
Investigate whether experience replay can preserve previous knowledge.

## Status
Completed.
