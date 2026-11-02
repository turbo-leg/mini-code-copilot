# Mini Code Copilot

A small Python code-completion project. It compares character n-gram models, word n-gram models, and an AST-based predictor, then integrates two selected models into a basic text editor.

## Project plan

- **Weeks 6–7:** Confirm the topic and language, choose at least 10 source projects, document sources and licenses, define evaluation metrics, and explore parsing and editor libraries.
- **Week 8:** Set up the project, collect and inspect the dataset, remove duplicates, and split projects into 70% training and 30% testing.
- **Week 9:** Build and evaluate character n-gram models for n=1 through 10, using smoothing for unseen sequences.
- **Week 10:** Build word n-gram models for n=1 through 10 and an AST-based predictor that handles incomplete code contexts.
- **Week 11:** Evaluate all models on held-out contexts with next-word accuracy and edit distance; compare results and choose a best model.
- **Week 12:** Integrate the best model and one alternative into a basic editor; compare the coding experience and document findings.
- **Week 13:** Prepare and give the project presentation; demonstrate both models and discuss results and limitations.
- **Week 14:** Finalize the report, code, dataset references, evaluation results, and required deliverables.

## Planned evaluation

Use next-word accuracy and Levenshtein edit distance between the suggested and expected word. Keep test projects separate from training projects to reduce data leakage. Record individual results for every n value and for the AST predictor.

## Planned tools

Python standard library for data handling and n-gram counts; Parso for tolerant Python parsing; RapidFuzz for edit distance; Tkinter for the editor; Matplotlib for result charts; and `unittest` for tests. The models are intended to run locally without a hosted prediction API.

## Dataset

The project will use at least 10 Python projects. Add the project URLs, licenses, and collection notes to `DATA_SOURCES.md` before using the code.
