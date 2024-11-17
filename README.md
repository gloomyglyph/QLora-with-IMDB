
# **QLoRA with IMDB**

This repository contains an implementation of **Quantized Low-Rank Adaptation (QLoRA)** for fine-tuning large language models using the Hugging Face Transformers library. The project demonstrates how to leverage QLoRA to reduce memory and computational requirements while fine-tuning a model on the **IMDB movie reviews dataset** for sentiment analysis.

---

## **Contents**

- `QLoRA-with-IMDB.ipynb`: The main Jupyter Notebook containing code and explanations for the project.

---

## **Key Features**

- **4-bit Quantization**: Reduces the memory footprint of large language models using 4-bit precision for base weights.
- **LoRA Fine-Tuning**: Introduces low-rank adapters for task-specific fine-tuning with minimal trainable parameters.
- **Efficient Training**: Optimized to run on GPUs with limited memory, enabling fine-tuning on consumer-grade hardware.
- **Sentiment Analysis**: Fine-tuning is demonstrated on the **IMDB movie reviews dataset**.

---

## **How to Run**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/QLoRA-with-IMDB.git
   cd QLoRA-with-IMDB
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "QLoRA-with-IMDB.ipynb"
   ```

4. Follow the instructions in the notebook to replicate the results.

---

## **Dependencies**

- Python 3.8 or higher
- Hugging Face Transformers
- Accelerate
- BitsAndBytes
- PyTorch
- Jupyter Notebook

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## **References**

This project is part of the **Generative AI Engineering and Fine-Tuning Transformers** course provided by [Coursera](https://www.coursera.org/learn/generative-ai-engineering-and-fine-tuning-transformers/home/welcome), created in collaboration with top instructors and researchers. Special thanks to the course creators for their detailed and practical lessons on QLoRA and generative AI.

---

## **Acknowledgements**

- [Coursera](https://www.coursera.org) and the course team for their excellent materials on generative AI and fine-tuning transformers.
- [Hugging Face](https://huggingface.co) for their robust libraries and tools for model fine-tuning.
- The authors of the research paper introducing **QLoRA**: *Efficient Finetuning of Large Language Models with 4-bit Quantization*.

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

---
