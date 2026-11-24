# Neuro projects

Small computational neuroscience projects, each in its own folder with a
notebook, figures and a README. Together they go from a model neuron (01) to
real neurons in a mouse (02) to the EEG of meditating people (03).

| # | Project | Question | Status |
|---|---|---|---|
| 01 | [From RC circuit to spike](01-neuron-models/) | How does a neuron turn an input current into spikes? LIF and Hodgkin-Huxley models, f-I curves | done |
| 02 | [How real neurons fire](02-mouse-neuropixels/) | How differently do real neurons fire from the LIF ideal? Neuropixels recordings from mice, PSTH, Fano factor | done |
| 03 | [Meditation and mind wandering in the EEG](03-meditation-eeg/) | Can an EEG tell whether a meditator is absorbed in meditation or whether their mind has wandered off? Reanalysis of a published dataset, power spectra, cluster test, classifier | done |

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
I built all three projects with Claude Code (Anthropic's AI coding assistant)
as pair programmer. Claude drafted most of the code. I chose the topics, wrote
key parts myself, checked the results against theory, the textbook or the
original paper, and decided how to read them; the "What I learned" sections are
in my own words. Each project ended with a mock interview on its figures and
methods. Each project README says in a few sentences what was mine.
