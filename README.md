# Introduction
In the age of sophisticated Artificial Intelligence (AI) tools like ChatGPT, discerning between human and AI-generated text is increasingly challenging. This challenge has significant implications for academic integrity, particularly regarding college application essays. Our project, developed for the Google Hackathon, introduces Palm2 LLM. This model is finely tuned to differentiate between AI-generated and human-written text by analyzing writing style, structure, and content.

## Documentation
The datasets used for this project include:
- `mixed_train_essays.xlsx`
- `mixed_train_essays_1.xlsx`
- `mixed_train_essays_2.xlsx`

The dataset columns are defined as follows:
- `prompt_id`: Indicator of the essay prompt provided to the student, labeled as 0 or 1.
- `text`: The actual text content of the essay.
- `generated`: Indicates whether the essay was machine-generated or human-written.

### Model Tuning Results
The results of the model tuning are documented in `Model Training data.xlsx`, which includes the following columns:
- `Tuned Model`: Identifier for the model after optimization.
- `Model ID`: Unique ID for referencing the tuned model.
- `Base Model`: The initial pre-trained model architecture used as the starting point for tuning.
- `Total Training Time`: The total time spent on training the model.
- `Tuned Examples`: The number of examples used during the model tuning process.
- `Epochs`: The number of complete passes through the training dataset.
- `Batch Size`: The quantity of examples processed together in one training iteration.
- `Learning Rate`: The size of the steps taken in the model's parameter space during training.

## References
- Zinshteyn, M., & Jones, C. (2023, October 23). Academic Officials Struggle to Find out If AI Wrote Students’ College Essays.
- Jules King, Perpetual Baffour, Scott Crossley, Ryan Holbrook, Maggie Demkin. (2023). LLM - Detect AI Generated Text. Kaggle. [https://kaggle.com/competitions/llm-detect-ai-generated-text](https://kaggle.com/competitions/llm-detect-ai-generated-text)
- Cingillioglu, I. (2023). Detecting AI-generated essays: the ChatGPT challenge. International Journal of Information and Learning Technology. [https://doi.org/10.1108/IJILT-03-2023-0043](https://doi.org/10.1108/IJILT-03-2023-0043)
