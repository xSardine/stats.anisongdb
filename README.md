# AMQ Stats

Repository to generate statistics from AMQ data.

## Installation

### Development environment

Requirements :

- Python ^3.10
- Jupyter
- Quarto

Create a virtual environment :

```bash
python -m venv .venv
```

Activate the virtual environment :

```bash
source .venv/bin/activate
```

Install the dependencies :

```bash
pip install -r requirements.txt
```

### Run the project

Place the data in a `data/raw` folder.

Render the HTML :

```bash
quarto render stats --output-dir ../docs/
```

This will generate the HTML file in the `docs` folder.

Preview the HTML file in your browser :

```bash
quarto preview stats --output-dir ../docs/
```

This will run a preview of the quarto document in your browser.

To publish it on github pages :
```bash
quarto publish gh-pages
```

## Licence

The source code is published under [MIT licence](LICENSE).  
Data will not be shared, so yes, this repo is useless.
