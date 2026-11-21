After running the notebook, copy these files from Google Drive (`MyDrive/exaggeration_lora/`) into this folder:

- `comparison.csv`: the main results table
- `all_predictions.csv`: every approach's prediction for each test pair
- `preds_zero_shot.csv`, `preds_cot.jsonl`, `preds_ft_direct.csv`, `preds_ft_strength.csv`: raw option scores
- `scenarios.csv`: scenario and crash-test outputs, including CoT reasoning
- `results_chart.png`: macro-F1 chart for the slides

The notebook reuses these instead of recomputing them.

The LoRA adapters (`lora_direct/`, `lora_strength/`) are not tracked in git. Upload them as a GitHub release or to
the Hugging Face Hub if you want others to skip training.
