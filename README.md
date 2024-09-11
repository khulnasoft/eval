### HumanEval for GPT-3.5/GPT-4

To generate the completions (after pip installing the requirements), run:

```
mkdir results
python run.py
```

Then to evaluate the completion results, run

```
pip3 install -e .
evaluate_functional_correctness results/name_of_results_file
```
