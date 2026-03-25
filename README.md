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
├── notebooks/               # Jupyter notebooks for exploration & Reproducibility
├── plots/                   # Generated figures and visualizations
├── README.md                # Project overview
├── requirements.txt         # Python dependencies
└── .gitignore               # Files Git should ignore
```

## Experiment 1 - DEA — Completed
I completed the first Differential Exposure Analysis (DEA) experiment and saved the interactive notebook and generated plots in this repository. See the files below for the reproducible run and visualizations.

- Notebook: `notebooks/01-task-1-baseline/`
- Plots: `plots/Task-1/`

Brief summary: The initial DEA run produced exposure visualizations (exposure by type and exposure vs frequency) from the experiment data. The notebook contains the code, inputs, and steps to reproduce the figures.

open `notebooks/Experiment-1.ipynb` directly in Colab by uploading the file.

## Experiment 2 - RAG — Completed
I completed the second experiment focusing on integrating Retrieval-Augmented Generation (RAG) into the current pipeline and saved the notebooks and plots in this repository. See the files below for the reproducible run.

- Notebooks: `notebooks/02-task-2-RAG/`
- Plots: `plots/Task-2/`

Brief summary: This experiment investigates privacy leakage in when RAG systems are used. The notebooks contain the code, inputs, and steps to reproduce the results.

## Experiment 3 - RAG vs Baseline LLM Comparison on Data Extraction Attacks
I completed the third experiment focusing on evaluating the impact of Retrieval-Augmented Generation (RAG) into the current pipeline on Data Extraction Attacks. See the files below for the reproducible run. This experiment is improvement of experiment 2 with more detailed design and evaluation metrics. I had to run 30+ runs to achieve the desired accuracy and results

- Notebooks: `notebooks/03-task-3-comparison/`
- Plots: `plots/Task-3/`
- 30+ Runs: `notebooks/ALL EXPERIMENTS/experiment-3-runs/`

Brief summary: This experiment investigates the effects and reduction of data extraction on training data when RAG is implemented. The notebooks contain the code, inputs, and steps to reproduce the results.

## Experiment 4 - RAG Ablation and Defensive Strategies
I completed the fourth experiment exploring ablation studies on RAG architecture variants and defensive strategies. This run generated insights on how retrieval noise, prompt filtering, and model checkpoints alter leakage behavior. See the notebook and plots for a detailed evaluation of attack success rates and defense impact.

- Notebooks: `notebooks/04-task-4-ablation-rag/`
- Data: `notebooks/04-task-4-ablation-rag/ablation-study/`

Brief summary: This experiment evaluates multiple RAG design choices (query selection, knowledge cutoff, and adversarial prompts) and the mitigation power of simple heuristics. Results show practical settings that reduce exposure while retaining utility.

## Experiment 5 - Shortest DEA Path Analysis
I completed the fifth experiment on shortest-path DEA analysis for a refined privacy risk estimate. The experiment extends baseline DEA with new exposure metrics and network-based analysis over many generated samples. It also compares baseline model leakage against optimized scoring thresholds.

- Notebooks: `notebooks/05-task-5-shortest-dea/`

Brief summary: This experiment introduces a shortest-path DEA variant and demonstrates clearer privacy-risk patterns, helping clarify when leakage spikes correlate with particular training segments.

## Experiment 6 - Dijkstra Ablation on Privacy Metrics
I completed the sixth experiment focusing on Dijkstra-style ablation and metric aggregation. The run further explores path-based privacy inference and system-level robustness across parameters. The results are in the notebook and dynamic chart outputs.

- Notebooks: `notebooks/06-djiktsra-ablation/`

Brief summary: This experiment validates that ablation across path edges can unearth high-risk exposure clusters and supports practical recommendations for model hardening and evaluation frameworks.


## Setup
```bash
# Clone repository
git clone https://github.com/syedahmedkhaderi/llm-privacy-research.git
cd llm-privacy-research
```

## Advisors
- Dr. Lamiaa Basyoni
- Dr. Karima Makhlouf
- Dr. Sami Zhioua

## Contact
Syed Ahmed Khaderi
syedahmedkhaderi@gmail.com
