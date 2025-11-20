# Multi-Agent LLM-Driven Framework for Enhanced EHR Modeling and Clinical Outcome Prediction (Demo)

This project implements a multi-agent LLM framework to enhance prediction and interpretation of clinical outcomes for ICU patients.

The system integrates a deep learning EHR model (RETAIN) with multiple LLM agents that leverage clinical guidelines, research literature, and structured EHR signals to produce transparent, clinically aligned reports.

# 📊 Dataset

**Source:** [MIMIC-IV (v3.1)](https://physionet.org/content/mimiciv/3.1/)

**Population:** ICU patients with AKI + tubular necrosis diagnosis

**Data:** Demographic info, Lab test features, vitals

# Tasks
In-hospital Mortality Prediction

# 🚀 Overview of the Framework


# Multi-Agents Systems (MAS)

**Data Agent**: Converts EHR model outputs into an LLM-readable patient summary

**RAG Agent**: Retrieves external knowledge

**Research Doctor Agent**: Leverages lastest research papers to provide evidence-based insights.

**Protocol Doctor Agent**: Uses clinical practical guidelines to inform practical recommendations.

**Leader Agent**: Summarizes and coordinates outputs from the two doctor agents.

# Corpus
**1. medical guideline**: [Merck Manual of Diagnosis and Therapy (professional version)](https://www.msdmanuals.com/professional)

**2. lastest research**: [PubMed](https://pubmed.ncbi.nlm.nih.gov/)
