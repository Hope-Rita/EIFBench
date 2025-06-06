# EIFBENCH: Extremely Complex Instruction Following Benchmark for Large Language Models

## Evaluation Procedure

**Step 1:** Configure your API key and endpoint URL within the `./configs/config.yaml` file to enable output generation.

**Step 2:** Integrate the API key and endpoint URL for GPT-4o or other state-of-the-art large language models in the evaluation script, specifically within `6_evaluation.py`.

**Step 3:** Execute the evaluation by specifying the filename and desired dataset category for assessment.

Utilize the following commands:

 ```bash
  bash eval.sh gpt4o party
  bash eval.sh gpt4o dialogue
  bash eval.sh gpt4o single
