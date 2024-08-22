# Official repository for the [paper](https://arxiv.org/abs/2407.11660): *"Soda-Eval: Open-Domain Dialogue Evaluation in the age of LLMs"*

```
@misc{mendonça2024sodaevalopendomaindialogueevaluation,
      title={Soda-Eval: Open-Domain Dialogue Evaluation in the age of LLMs}, 
      author={John Mendonça and Isabel Trancoso and Alon Lavie},
      year={2024},
      eprint={2408.10902},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2408.10902}, 
}
```

## Soda-Eval

You can load the Soda-Eval dataset from the [HuggingFace hub](https://huggingface.co/datasets/Johndfm/soda_eval) as the following:

```python
from datasets import load_dataset

raw_datasets = load_dataset("Johndfm/soda_eval")

train_dataset = raw_datasets["train"]
val_dataset = raw_datasets["val"]
test_dataset = raw_datasets["test"]
```
