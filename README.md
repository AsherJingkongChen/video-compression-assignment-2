# Video Compression Assignment 2

## Task Descriptions

See the [`resources/assignment.pdf`](./resources/assignment.pdf) for more information.

## Solutions and outputs

See the [`notebooks/assignment.ipynb`](./notebooks/assignment.ipynb) for the solutions and outputs.

The PDF report from the notebook can be found at [`docs/README.pdf`](./docs/README.pdf)

## Development

### Prerequisites

- Programming langauge: Python 3.10+ (IPython)
- Framework: Jupyter

```shell
pip install -Ur requirements.txt
```

### Formatting

```shell
python -m black --line-length 80 . 
```

### Printing PDF

```shell
jupyter nbconvert --to webpdf --output README --output-dir docs/ notebooks/assignment.ipynb
```
