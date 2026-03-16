# Data and Prompts for Two-Stage LLM-as-a-Judge

This repository contains the human evaluation data and prompt templates
used in the paper "Two-Stage LLM-as-a-Judge Using Required and Bonus Items".

## Contents

### `prompt/`
Prompt templates used in our experiments, adapted from Cook et al. (2024) and extended to support multi-turn evaluation.

- `required_items_generation_turn1.md`: Prompt for generating required items (Turn 1)
- `required_items_generation_turn2.md`: Prompt for generating required items (Turn 2)
- `bonus_items_generator_turn1.md`: Prompt for generating bonus items (Turn 1)
- `bonus_items_generator_turn2.md`: Prompt for generating bonus items (Turn 2)
- `evaluator_turn1.md`: Prompt for the evaluator LLM (Turn 1)
- `evaluator_turn2.md`: Prompt for the evaluator LLM (Turn 2)

### `human_eval/`
Human evaluation data collected from three American annotators holding doctoral degrees via Prolific.

- `human_evaluation.csv`: Human evaluation results for MT-Bench (Writing, Roleplay, Humanities, and STEM categories)
