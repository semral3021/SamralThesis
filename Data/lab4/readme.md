README — Real Prompt Examples for AI Agent
This folder contains two prompt examples that demonstrate how the thesis system (Semantic Fiction Analysis Agent) works as an end-to-end AI solution.
Each prompt gives the agent an input text X (a fictional scene) and expects the agent to produce the semantic output y.
________________________________________
Prompt 1 — Zero-Shot Example
File: prompt1_zero_shot.txt
This prompt provides the agent with one new fictional scene X and no prior examples.
The agent must process the text fully on its own, including:
•	basic text understanding
•	entity and character extraction
•	theme and topic inference
•	sentiment and emotional tone detection
•	narrative function identification
•	final semantic output generation
The output (y) includes:
1.	Characters
2.	Named entities
3.	Themes
4.	Sentiment and emotional tone
5.	Narrative function
6.	Character–theme relationships
7.	Keywords
The zero-shot prompt tests whether the system can analyze a scene without any previous guidance.
________________________________________
Prompt 2 — Few-Shot Example
File: prompt2_few_shot.txt
This prompt first provides several known (X, y) examples to show the agent what type of interpretation is expected.
After the examples, a new fictional scene X is given, and the agent is asked to generate the correct y.
The output format is the same as in the zero-shot prompt:
•	characters
•	entities
•	themes
•	sentiment and tone
•	narrative role
•	relationships and keywords
The few-shot prompt demonstrates how the agent improves consistency and reasoning when given examples.
________________________________________
Difference Between the Prompts
Zero-shot:
The agent receives only a new text X and must produce the semantic output y from scratch.
Few-shot:
The agent receives several example (X, y) pairs before generating y for a new input.
________________________________________
Purpose of These Prompts
These prompts show how the thesis system can function as a single AI agent that transforms fictional text into a structured semantic analysis.
They serve as documentation and demonstration for the project requirement.

