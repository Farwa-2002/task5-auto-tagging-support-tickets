# Task 5: Auto Tagging Support Tickets Using LLM

## Objective
Automatically classify support tickets into categories using a Large Language Model.

## Methodology
- Used Hugging Face zero-shot classification model (BART)
- Implemented zero-shot and few-shot learning
- Predicted top 3 tags per ticket

## Technologies Used
- Python
- Transformers (Hugging Face)
- Pandas
- Matplotlib

## Results
- Zero-shot learning provided good baseline results
- Few-shot prompting improved classification accuracy
- Model successfully generated top 3 tags

## Conclusion
LLMs can effectively automate support ticket classification without training, saving time and effort.