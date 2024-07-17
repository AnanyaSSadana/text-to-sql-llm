# Text-To-SQL Context-Aware Query System

## Overview
This project implements a Text-to-SQL system that generates context-aware SQL queries using large language models (LLMs) augmented with Retrieval Augmented Generation (RAG). The system is fine-tuned for effective performance on educational datasets and provides a user-friendly interface for querying and interacting with the Integrated Postsecondary Education Data System (IPEDS).

## Technologies Used
- **Huggingface**: For utilizing pre-trained language models.
- **LangChain**: For building and managing the context-aware query system.
- **ChromaDB**: For managing and retrieving the context data.
- **Python**: As the primary programming language.

## Features
- **Context-Aware SQL Generation**: Utilizes LLMs with RAG to create accurate and contextually relevant SQL queries.
- **Parameter Efficient Fine Tuning (PEFT)**: Fine-tuned Llama2-7b model using LoRA adapters on WikiSQL & Spider datasets.
- **User-Friendly Interface**: Designed an intuitive interface for interacting with IPEDS data.

## Datasets
- **WikiSQL**: For training and evaluating SQL query generation.
- **Spider**: For enhancing the system's performance on complex queries.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
