# Privacy Leakage in LLMs using PETs
Research project investigating privacy leakage in Large Language Models and mitigation using Privacy Enhancing Technologies.

## Project Overview
This research explores how Large Language Models can accidentally leak sensitive training data and how Privacy Enhancing Technologies (PETs) like Differential Privacy can prevent this.

## Research Questions
1. How do LLMs memorize and leak sensitive information?
2. Can Privacy Enhancing Technologies effectively prevent leakage?
3. What is the trade-off between privacy and model performance?


## Project Structure
```
llm-privacy-research/
├── data/                    # All datasets
│   ├── raw/                 # Original, untouched data
│   ├── processed/           # Cleaned, ready-to-use data
│   └── synthetic/           # Fake data you generate for testing
├── code/                    # All your Python code
│   ├── experiments/         # Main experiment scripts
│   ├── utils/               # Helper functions (reusable code)
│   └── models/              # Model training/testing code
├── docs/                    # Documentation
│   ├── literature/          # Paper summaries, notes from reading
│   ├── notes/               # Daily research notes
│   └── meetings/            # Meeting notes with professors
├── results/                 # All outputs from experiments
│   ├── figures/             # Graphs, charts, visualizations
│   ├── logs/                # Experiment logs (what happened during runs)
│   └── outputs/             # Model outputs, results files
├── notebooks/               # Jupyter notebooks for exploration
├── README.md                # Project overview 
└── .gitignore               # Files Git should ignore
```

# Privacy Leakage in LLMs using PETs

Research project investigating privacy leakage in Large Language Models and mitigation using Privacy Enhancing Technologies.

## Project Overview
This research explores how Large Language Models can accidentally leak sensitive training data and how Privacy Enhancing Technologies (PETs) like Differential Privacy can prevent this.

## Research Questions
1. How do LLMs memorize and leak sensitive information?
2. Can Privacy Enhancing Technologies effectively prevent leakage?
3. What is the trade-off between privacy and model performance?


## Setup
```bash
# Clone repository
git clone https://github.com/syedahmedkhaderi/llm-privacy-research.git
cd llm-privacy-research

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Progress
- [x] Environment setup
- [ ] Literature review
- [ ] Baseline experiments
- [ ] PET implementation
- [ ] Results analysis

## Advisors
- Dr. Lamia Makhlouf
- Dr. Karima Makhlouf
- Dr. Sami Zhioua

## Contact
Syed Ahmed Khaderi
syedahmedkhaderi@gmail.com