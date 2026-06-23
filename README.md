# Feed an AI-agentic beast with proper data 
### Presentation: Feed an AI-agentic beast with proper data (workshop/presentation.pdf)

## Workshop description
During the workshop you will learn how to prepare your data so your agent isn't flying blind. We'll work through examples, such as:
- cleaning and contextualizing tabular data
- chunking documents intelligently 
- and building habits for reviewing AI-generated code with confidence.

## Requirements
Python >= 3.10.
<!-- * PyLadies Amsterdam uses [uv](https://docs.astral.sh/uv/) for dependency management
* Google account if you want to use [Google Colab](https://colab.research.google.com/) -->
 
## Usage
### with uv
```bash
git clone https://github.com/pyladiesams/feed-AI-agentic-beast-proper-data-jun2026
cd feed-AI-agentic-beast-proper-data-jun2026
```

#### create and activate venv, install dependencies
```bash
uv sync
```

### with other systems
- Clone the repository:
    ```bash
    git clone https://github.com/pyladiesams/feed-AI-agentic-beast-proper-data-jun2026
    cd feed-AI-agentic-beast-proper-data-jun2026
    ```
- Install requirements:
    ```bash
    pip install -r requirements.txt
    ```
- Start jupyter notebook by navigating to the workshop folder

### for a workshop giver
To get started, open the `pyproject.toml` file and set the required Python version. The minimum supported version is 3.10.

After you have specified the Python version, you can create a virtual environment with `uv venv` and add packages with `uv add <package>`. Before the workshop, you can generate a requirements.txt file, which is needed e.g. for running code in Google Colab, by running `uv export --no-dev > requirements.txt`.

## Video record
Re-watch [this YouTube stream](https://www.youtube.com/live/2EnszJLzzAc)

## Credits
This workshop was set up by @pyladiesams and @jessica-eggen

<!-- ## Appendix
### Pre-Commit Hooks

To ensure our code looks beautiful, PyLadies uses pre-commit hooks. You can enable them by running `pre-commit install`. You may have to install `pre-commit` first, using `uv sync`, `uv pip install pre-commit` or `pip install pre-commit`. -->
