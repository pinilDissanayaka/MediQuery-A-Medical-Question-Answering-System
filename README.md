# MediQuery-A-Medical-Question-Answering-System

MediQuery is an advanced medical question-answering system leveraging the MedQuAD dataset, LangChain for orchestration, ChromaDB as a vector database, and Gemini as the large language model. This project aims to provide accurate and relevant medical information based on user queries, covering a wide range of medical topics.

## Features
- Accurate QA: Utilizes the MedQuAD dataset with over 47,000 question-answer pairs from reputable NIH sources.
- Advanced Search: Powered by ChromaDB to efficiently index and retrieve relevant information.
- State-of-the-Art NLP: Incorporates Gemini, a powerful large language model, for precise and context-aware answers.
- Annotation-Aware: Leverages detailed annotations for improved question understanding and answer relevance.
- Ethical Compliance: Ensures compliance with MedlinePlus copyright by respecting data usage guidelines.

## Installation
### Prerequisites
- Python 3.8+
- Git
- Virtualenv

### Clone the Repository
```
git clone https://github.com/yourusername/MediQuery.git
cd MediQuery
```
### Set Up Virtual Environment
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
### Install Dependencies
```
pip install -r requirements.txt
```

## Contributing
We welcome contributions to enhance MediQuery! Here are some ways you can contribute:

- Bug Reports & Feature Requests: Use the Issues section on GitHub.
- Code Contributions: Fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
[MedQuAD](https://www.kaggle.com/datasets/gvaldenebro/cancer-q-and-a-dataset) for the comprehensive medical dataset.
[LangChain](https://www.langchain.com/) for the orchestration framework.
[ChromaDB](https://www.trychroma.com/) for the vector database solution.
[Gemini](https://gemini.google.com/) for the powerful language model.
