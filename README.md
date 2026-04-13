# Modified-release-tablets
📌 Project Overview
This repository contains a systematically curated, literature-derived dataset focused on extended-release matrix tablet formulations. The project bridges the gap between traditional pharmaceutical technology and modern machine learning by providing structured data extracted from peer-reviewed research.

The dataset was generated using a hybrid approach: automated extraction via a state-of-the-art Large Language Model (GPT-5.2) followed by a human-in-the-loop validation protocol to ensure high fidelity and technical accuracy.

📊 Dataset Characteristics
The curated data (stored in JSON format) encompasses:

Formulation Composition: Quantitative mass fractions of APIs and excipients.

Process Parameters: Unit operations, compression force, equipment details, and coating conditions.

Pre-compression Data: Angle of repose, bulk/tapped density, etc.

Critical Quality Attributes (CQAs): Hardness, friability, thickness, and drug content.

In Vitro Performance: Detailed dissolution profiles and release kinetics.

🚀 Key Features
Semantic Harmonization: Raw entities are mapped to controlled vocabularies to resolve excipient naming synonyms.

ML-Ready: Structured specifically for exploratory data analysis (EDA), multivariate correlation, and as a training set for Small and Large Language Models (SLMs/LLMs).

Transparent Limitations: Data gaps and inconsistent reporting in original literature are explicitly annotated.

📂 Repository Structure
/data: Contains the curated dataset in .json format.

/scripts: (Opcjonalnie: skrypty do analizy danych lub przykłady EDA).

/docs: Additional documentation and terminology mapping.

🎯 Future Goals
This database serves as the foundation for developing an AI-powered Pharmaceutical Technologist Assistant. Future iterations will focus on domain-specific fine-tuning of models to provide context-aware recommendations for formulation scientists.
