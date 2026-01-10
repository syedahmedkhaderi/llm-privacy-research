# Privacy Leakage in LLMs using PETs
Research project investigating privacy leakage in Large Language Models and mitigation using Privacy Enhancing Technologies.

## Project Overview
This research explores how Large Language Models can accidentally leak sensitive training data and how Privacy Enhancing Technologies (PETs) like Differential Privacy can prevent this by running various experiments with different datasets and models.

## Project structure
```
llm-privacy-research/
├── research_papers/
├── docs/                    # Documentation and notes
│   ├── reports/             # Experiment Reports & Conclusion
│   ├── meetings/            # Meeting notes
│   └── notes/               # Daily research notes
├── notebooks/               # Jupyter notebooks for exploration
├── plots/                   # Generated figures and visualizations
├── README.md                # Project overview
├── requirements.txt         # Python dependencies
└── .gitignore               # Files Git should ignore
```

## Experiment 1 - DEA — Completed
I completed the first Differential Exposure Analysis (DEA) experiment and saved the interactive notebook and generated plots in this repository. See the files below for the reproducible run and visualizations.

- Notebook: `notebooks/Experiment-1.ipynb`
- Plots: `plots/Task - 1/Exposure by type/` and `plots/Task - 1/Exposure V Frequency/`

Brief summary: The initial DEA run produced exposure visualizations (exposure by type and exposure vs frequency) from the experiment data. The notebook contains the code, inputs, and steps to reproduce the figures.

open `notebooks/Experiment-1.ipynb` directly in Colab by uploading the file.

## Experiment 2 - RAG — Completed
I completed the second experiment focusing on integrating Retrieval-Augmented Generation (RAG) into the current pipeline and saved the notebooks and plots in this repository. See the files below for the reproducible run.

- Notebooks: `notebooks/Experiment-2-RAG/`
- Plots: `plots/Task-2/`

Brief summary: This experiment investigates privacy leakage in when RAG systems are used. The notebooks contain the code, inputs, and steps to reproduce the results.


## Setup
```bash
# Clone repository
git clone https://github.com/syedahmedkhaderi/llm-privacy-research.git
cd llm-privacy-research

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

## Advisors
- Dr. Lamiaa Basyoni
- Dr. Karima Makhlouf
- Dr. Sami Zhioua

## Contact
Syed Ahmed Khaderi
syedahmedkhaderi@gmail.com
