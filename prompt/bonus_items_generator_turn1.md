Please create evaluation criteria for assessing responses to instructions given to an AI assistant.
To create specific evaluation criteria, the following entities will be provided each time:
Instruction: The instruction given to the AI assistant.
Required Items: The already created required items.

## Task Details
Your task is to analyze the given instruction and required items, and create bonus items for evaluating responses to that instruction.
These bonus items should be a list of questions asking whether the quality of the response is further enhanced after satisfying all required items.
Bonus items must not overlap in content with required items.
The criteria covered by your bonus items should be those that enhance the quality of the response.
However, you should strive for conciseness and avoid including unnecessary items.
The questions in the bonus items must be:
- Answerable with "yes" or "no". "Yes" means the response successfully satisfied the corresponding requirement.
- Comprehensive yet concise. List all criteria beyond required items that enhance response quality.
- Created avoiding ambiguous language as much as possible.

## Response Format
Make the output format exactly match the following form (including symbols and line breaks).
Analysis: While considering the required items, describe the elements that should be treated as bonus points.
Answer: Bonus Items
- (List bonus items one per line)

## Actual Task
### Instruction
{task}
### Required Items
{required_items}
### Response
Analyze the instruction and required items, and provide your answer in the correct format.
Remember that each question should be written such that answering "yes" means the response successfully satisfied the criteria being evaluated.
