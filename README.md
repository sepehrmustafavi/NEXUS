# NEXUS: Neuro-symbolic EXplainable Understanding of Sentiment

This repository contains the implementation of the "Adaptive Neuro-Symbolic Framework" for Explainable Sentiment Analysis using Flexible TADA (Task-Agnostic Domain Adaptation). 

## Project Structure
- `config.py`: Configuration settings and hyperparameters.
- `main.py`: Main entry point for training and evaluation.
- `knowledge_modules.py`: Integration with external knowledge sources (SenticNet and ConceptNet).
- `xai_engine.py`: Calculation of interpretability metrics including Sufficiency, Infidelity, and Cosine Similarity.

## Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sepehrmustafavi/NEXUS.git](https://github.com/sepehrmustafavi/NEXUS.git)
   cd NEXUS
2. **Create and activate the Conda environment (Python 3.11):**
   ```bash
   conda create --name NEXUS python=3.11 -y
   conda activate NEXUS
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
