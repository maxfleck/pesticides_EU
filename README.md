## Pesticides

Merges active substances with pesticide names from EU database (the API is shit).
Result with one-shot PubChemAPI:

Result:
- 495/679 substances have SMILES (according to one-shot PubChem calls - should be more in the end)
- Missing SMILES (184): many of them should be obtainable using more advanced tools (see my mail) than "only" PubChemPy


### Quickstart:

install [uv package manager](https://docs.astral.sh/uv/getting-started/installation/)
```
curl -LsSf https://astral.sh/uv/install.sh | sh
```

then run (all packages will be downloaded and saved locally)
```
uv run jupyter-lab
```
...or use vs code. Then execute
```
code .
```
and select the uv environment.