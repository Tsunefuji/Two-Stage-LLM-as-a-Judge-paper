# Data and Prompts for Two-Stage LLM-as-a-Judge

This repository contains the human evaluation data and prompt templates
used in the paper "Two-Stage LLM-as-a-Judge Using Required and Bonus Criteria".

## Contents

### `prompt/`
Prompt templates used in the experiments, adapted from Cook et al. (2024) and extended to support multi-turn evaluation.

- `required_criteria_generation_turn1.md`: Prompt for generating required criteria (Turn 1)
- `required_criteria_generation_turn2.md`: Prompt for generating required criteria (Turn 2)
- `bonus_criteria_generator_turn1.md`: Prompt for generating bonus criteria (Turn 1)
- `bonus_criteria_generator_turn2.md`: Prompt for generating bonus criteria (Turn 2)
- `evaluator_turn1.md`: Prompt for the evaluator LLM (Turn 1)
- `evaluator_turn2.md`: Prompt for the evaluator LLM (Turn 2)

### `human_eval/`
Human evaluation data collected from three American annotators holding doctoral degrees via Prolific.

- `pairwise_evaluation.csv`: Human evaluation results for MT-Bench (Writing, Roleplay, Humanities, and STEM categories)
- `criteria_eval.csv`: Human evaluation results assessing the quality of the generated evaluation criteria.
- `criteria_judge_eval.csv`: Human evaluation results on whether the target model's responses satisfy the generated evaluation criteria.
