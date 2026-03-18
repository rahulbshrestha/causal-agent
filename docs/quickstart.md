# Quickstart
```python
from cais import CausalAgent

pipeline = CausalAgent()
pipeline.run_analysis(
    query="What is the causal effect of X on Y?",
    dataset_path="data.csv",
    dataset_description="..."
)
```