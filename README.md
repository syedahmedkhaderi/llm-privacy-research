# Privacy Leakage in LLMs using PETs
Research project investigating privacy leakage in Large Language Models and mitigation using Privacy Enhancing Technologies.

## Project Overview
This research explores how Large Language Models can accidentally leak sensitive training data and how Privacy Enhancing Technologies (PETs) like Differential Privacy can prevent this by running various experiments with different datasets and models.

## Project structure
```
llm-privacy-research/
├── docs/                    # Documentation and notes
│   ├── reports/             # Experiment Reports & Conclusion
│   │   ├── latex-code       # Latex code of reports
│   ├── meetings/            # Meeting notes
│   └── notes/               # Daily research notes
|
├── notebooks/               # Jupyter notebooks for exploration
│   └── Experiment-1.ipynb   # DEA experiment notebook (completed)
|
├── plots/                   # Generated figures and visualizations
│   ├── Task - 1/
│   │   ├── Exposure by type/
│   │   └── Exposure V Frequency/
│   └── Task-2/
|
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
- Dr. Lamia Makhlouf
- Dr. Karima Makhlouf
- Dr. Sami Zhioua

## Contact
Syed Ahmed Khaderi
syedahmedkhaderi@gmail.com
