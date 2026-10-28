# Choosing Letters in Hangman

**Which letter should be guessed next when only part of a word is visible?**

The solver uses character sequences in both directions, up to five characters long, to score candidate guesses from the revealed pattern and previous guesses. This is a statistical language-model approach rather than a neural large language model.

## Inspect the work

[Open the notebook](New_hangman_api_user%20%281%29.ipynb)

Read the imports and data-loading cells before running this historical notebook. Install a compatible environment and run from this folder; this documentation review did not rerun the model.

## Interpretation

The notebook includes an API-oriented game workflow. Inspect its configuration and dictionary assumptions before running it. No current API availability, held-out win rate or optimality claim is made; the historical notebook was not re-evaluated here.

[Earlier-project index](../README.md) · [Current portfolio](https://github.com/Fakhruddin12)
