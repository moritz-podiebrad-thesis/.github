# Designed to Debunk – Master's thesis

Code and data of the master's thesis *Designed to Debunk: Anforderungsanalyse und
Datensatzkonstruktion für ausgewählte XAI-Modelle zur Detektion von Desinformation
im digitalen Raum* (Ulm University, Institute of Business Analytics, 2026), written
in the context of the BMFTR project
[EKILED](https://www.forschung-it-sicherheit-kommunikationssysteme.de/projekte/ekiled) by [Moritz Podiebrad](https://github.com/moritz-podiebrad).

This thesis builds a dataset of German social media posts annotated with ten
linguistic-rhetorical concepts which serves as training data for explainable
disinformation detection models. Following a Design Science Research approach,
it also collects design knowledge on annotating such concepts with LLMs.

Working copy of thesis can be found [here](https://github.com/moritz-podiebrad-thesis/EKILED-XAI-Dataset/blob/main/docs/thesis_working_version.pdf) (last updated: 22.11.2026).

## Repositories

| Repository | Content |
|---|---|
| [EKILED-XAI-Dataset](https://github.com/moritz-podiebrad-thesis/EKILED-XAI-Dataset) | Builds the input datasets, evaluates the LLM annotations and merges them into the released dataset |
| [ekiled-llm-annotation-mpo](https://github.com/moritz-podiebrad-thesis/ekiled-llm-annotation-mpo) | Zero-shot concept annotation with open-weight LLMs, via vLLM on a Slurm cluster or any OpenAI-compatible endpoint |

Data flow: EKILED-XAI-Dataset → input JSONL → ekiled-llm-annotation-mpo → result
JSONL → EKILED-XAI-Dataset.

## Access

All repositories are private. Access is available on request.
