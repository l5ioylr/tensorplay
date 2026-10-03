# tensorplay

Tiny CNN experiments on synthetic image data

## Getting started

```bash
pip install -r requirements.txt
```

## How to use

```bash
python train.py --epochs 5 --synthetic
# metrics land in runs/metrics.csv
```

## What it does

- Synthetic dataset mode: no download needed to smoke-test
- Metrics logged to CSV for plotting
- Cosine LR schedule with warmup
- Single file model definition, easy to hack
- Gradient clipping and clean metrics logging

## Project structure

```text
├── docs/
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── model.py
├── requirements.txt
└── train.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT - see [LICENSE](LICENSE).
