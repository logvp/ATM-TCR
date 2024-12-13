# ATM-TCR

This branch is the **unmodified** model from https://github.com/Lee-CBG/ATM-TCR for CSE 494/559.

## Unmodified

The unmodified model and weights are in the git branch [`main`](https://github.com/logvp/ATM-TCR/tree/main) which runs the original model with no major changes.
The trained weights are in the `main` branch at `models/[epi,tcr]_def_trained.ckpt`, named for which split of the provided data it was trained on.

## Modifications

The modified model and weights are in the git branch [`pos`](https://github.com/logvp/ATM-TCR/tree/pos) which adds positional dependance to the embedding step.
The trained weights are in the `pos` branch at `models/[epi,tcr]_pos_trained.ckpt`, named for which split of the provided data it was trained on.

The model was trained using ASU Research Computing's [Sol Supercomputer](https://dl.acm.org/doi/10.1145/3569951.3597573)
