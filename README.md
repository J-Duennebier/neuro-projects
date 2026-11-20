# Neuro projects

Small computational neuroscience projects, each in its own folder with a
notebook, figures and a README.

| # | Project | Question | Status |
|---|---|---|---|
| 01 | [From RC circuit to spike](01-neuron-models/) | How does a neuron turn an input current into spikes? LIF and Hodgkin-Huxley models, f-I curves | done |
| 02 | [How real neurons fire](02-mouse-neuropixels/) | How differently do real neurons fire from the LIF ideal? Neuropixels recordings from mice, PSTH, Fano factor | in progress |

More projects will follow in this repository.

## Running the notebooks
```bash
python -m venv .venv
.venv\Scripts\activate        # Windows; on macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
```
Then open a project's notebook in Jupyter or VS Code and run all cells. Figures
are written to the project's `figures/` folder.

## How this was built
The projects were built with Claude Code (Anthropic's AI coding assistant) as
pair programmer and tutor. Each project README has a section "How this was
built" that says what was mine and what was Claude's.
