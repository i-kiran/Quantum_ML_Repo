# Quantum × Machine Learning (QML) Hub

A community-maintained hub of **papers, datasets, tools, benchmarks, libraries, and tutorials** at the intersection of **quantum computing** and **machine learning** (QML).  
This repository goes beyond a single README: it is a structured knowledge base with folders for **papers**, **code notebooks**, **benchmarks**, **datasets**, **tutorials**, and **tools**.

## Goals
- Provide a **clear map** of QML: what it is, why it matters, and where to start.
- Curate **high-quality, categorized resources** with lightweight summaries and tags.
- Offer **reproducible examples** (notebooks) and **baseline benchmarks**.
- Encourage **open contributions** via Issues/PRs with simple templates.

## Who is this for?
- Researchers exploring variational quantum algorithms, QML theory, or hybrid models
- Practitioners prototyping QNNs, VQCs, QAOA/QML pipelines, or quantum-enhanced kernels
- Students looking for structured **on-ramps** and hands-on notebooks

---

## Repository Map

```
.
├─ README.md
├─ CONTRIBUTING.md
├─ CODE_OF_CONDUCT.md
├─ LICENSE
├─ CITATION.cff
├─ .github/
│  ├─ issue_template.md
│  └─ pull_request_template.md
├─ docs/
│  ├─ roadmap.md
│  └─ glossary.md
├─ papers/
│  ├─ surveys/
│  ├─ foundations/
│  ├─ models/
│  ├─ applications/
│  └─ reading-lists/
├─ datasets/
│  ├─ synthetic/
│  └─ real-world/
├─ benchmarks/
│  ├─ baselines/
│  └─ leaderboards/
├─ tutorials/
│  ├─ beginner/
│  ├─ intermediate/
│  └─ advanced/
├─ notebooks/
│  ├─ intro/
│  ├─ variational/
│  ├─ kernels/
│  └─ hybrid/
├─ tools/
│  ├─ frameworks/
│  │  ├─ qiskit-ml/
│  │  ├─ pennylane/
│  │  ├─ tensorflow-quantum/
│  │  ├─ cirq/
│  │  └─ torchquantum/
│  └─ utilities/
└─ awesome/
   ├─ libraries.md
   ├─ tutorials.md
   ├─ datasets.md
   └─ benchmarks.md
```

---

## Quick Start

- Browse curated lists in **/awesome** and deeper notes in **/docs**
- Run example notebooks in **/notebooks** (requires Python 3.10+)
- Try a framework scaffold under **/tools/frameworks/**

```bash
# Recommended: create env
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt

# Open notebooks
jupyter lab
```

> See `requirements.txt` for a minimal starter set (you can uncomment extras).

---

## Contributing

We welcome issues and PRs. See **CONTRIBUTING.md** for guidelines and a checklist.  
Please follow the **CODE_OF_CONDUCT.md**.

---

## Citation

If this repository is useful in your research, please cite it (see **CITATION.cff**).

---

## License

MIT License (see **LICENSE**).
