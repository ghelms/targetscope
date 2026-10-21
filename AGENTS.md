# AGENTS.md — TargetScope

## Project context

TargetScope is a scientific bioinformatics project focused on reproducible analysis and therapeutic target prioritization in cancer.

The project uses Python and R and must remain compatible with a Mac with 8 GB RAM.

## Development rules

1. Prefer simple, readable and maintainable solutions.
2. Explain the intended implementation before making substantial changes.
3. Make small, reviewable changes.
4. Write or update tests for new functionality.
5. Do not introduce unnecessary dependencies.
6. Do not download large datasets without approval.
7. Never commit raw biological datasets, credentials or secrets.
8. Prefer CPU-compatible and memory-efficient implementations.

## Scientific integrity

1. Do not independently select or change statistical methods.
2. Do not infer biological conclusions from computational outputs.
3. Do not invent biological evidence, citations or results.
4. Do not change filtering thresholds or analysis parameters without approval.
5. Document assumptions, provenance and limitations.
6. Keep scientific calculations independent of generative AI.

## Python and R

- Python: use clear type annotations where practical, pytest and Ruff.
- R: use readable functions, explicit package dependencies and appropriate testing.
- Separate reusable analysis code from exploratory notebooks.
- Keep configurations explicit and version-controlled.

## Before completing a task

- Summarize all changed files.
- Report tests run and their outcomes.
- Identify untested functionality.
- Flag scientific assumptions requiring human review.
- Do not claim that tests passed unless they were executed successfully.
