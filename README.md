# MCQ Question Answering using Llama 3.1(On going Project)

This project focuses on solving Multiple-Choice Questions (MCQ) using the Llama 3.1 model with 8.1 billion parameters (instruct version). The task involved answering questions with four options, both without fine-tuning and with fine-tuning using LoRA.

## Features
- **Model Used:** Llama 3.1 (8.1 billion parameters, instruct version).
- **MCQ Format:** Questions with four options.
- **Fine-Tuning Techniques:**
  - Without fine-tuning.
  - With fine-tuning using **Low-Rank Adaptation (LoRA)**.

## Project Workflow
1. **Dataset Preparation:**
   - Collected and preprocessed a dataset of MCQs.
   - Ensured compatibility with the input format required by Llama 3.1.

2. **Model Evaluation Without Fine-Tuning:**
   - Directly tested the Llama 3.1 model on the dataset.
   - Measured performance metrics such as accuracy.

3. **Fine-Tuning with LoRA:**
   - Applied Low-Rank Adaptation (LoRA) to fine-tune the model on the dataset.
   - Improved model performance through task-specific adaptations.

4. **Performance Comparison:**
   - Compared results of the model with and without fine-tuning.

## Results
- Achieved improved accuracy and consistency in answering MCQs after fine-tuning with LoRA.
- **Accuracy Improvement:** Increased from 76.82% (without fine-tuning) to 92.8% (with fine-tuning).

## Technologies Used
- **Python**
- **Llama 3.1 (8.1B instruct)**
- **LoRA (Low-Rank Adaptation)**


## How to Use
### Requirements
- Python 3.8+
- Required libraries: `transformers`, `accelerate`, `lora`, `numpy`, `pandas`

Clone this repository:
   ```bash
   git clone https://github.com/mahshar-yahan/MCQLlama3.1.git
   cd mcq-qa-llama

## Future Work
- Explore other fine-tuning methods for improved performance.
- Test on larger datasets with diverse question formats.
- Extend the system to handle multi-modal MCQs (text and image).

## Acknowledgments
- **Llama 3.1 Model** for providing a robust base for this task.
- **LoRA** for enabling efficient fine-tuning.
