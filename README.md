# NLP Question Answering with Fine-Tuning Project
NLP question answering fine tuning Hugging Face's transformers

## Overview

This project demonstrates Question Answering (QA) with Fine-Tuning using the Stanford Question Answering Dataset (SQuAD) from the original source. It aims to provide a simple guide on how to fine-tune a transformer-based model for QA tasks using custom datasets.

## Table of Contents

- [Setup](#setup)
- [Fine-Tuning](#fine-tuning)
- [Inference](#inference)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)


## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/qa-fine-tuning-project.git
   cd qa-fine-tuning-project
   ```

2. Install dependecies:

```bash
    pip install -r requirements.txt
```

## Fine-tuning

- Use the fine-tuning.ipynb notebook to fine-tune your transformer-based model on the custom SQuAD dataset.
- You can modify hyperparameters and experiment with different models.

## Inference

Use the inference API from transformers:

```python
# Use a pipeline as a high-level helper
from transformers import pipeline

pipe = pipeline("question-answering", model="jolual2747/qa_nlp_model")
```

## Results
See Hugging Face model card [here.](https://huggingface.co/jolual2747/qa_nlp_model)


## Contributing
Contributions are welcome! If you have suggestions or improvements, please create an issue or a pull request.

## License
This project is licensed under the Apache 2.0 License.



