# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarisation.

## Scenario:

### Step 1:

Summarise the following 500-word article on “The Basics of Blockchain Technology” in 120–150 words for undergraduate students. Keep it clear and beginner-friendly.


### Step 2 (Feedback):

Please revise the summary to simplify it and include at least two real-world examples of blockchain applications.

## Algorithm
1.	Input Preparation:
o	A ~500-word article was written on “The Basics of Blockchain Technology.”
o	This served as the common input for all AI models.
2.	Prompt Design (Step 1):
o	Each AI model was given the same instruction:
“Summarise this article on ‘The Basics of Blockchain Technology’ in 120–150 words for undergraduate students. Keep it clear and beginner-friendly.”
o	This tested zero-shot / direct prompting performance.
3.	Feedback Refinement (Step 2):
o	Each AI was then instructed:
“Make this summary even simpler and include at least two real-world examples of blockchain applications.”
o	This tested iterative / feedback-based prompting.
4.	Prompting Techniques Applied:
o	Zero-Shot Prompting: Asking directly without examples (used for Step 1).
o	Role-Based Prompting: Instructing the model to act like a teacher/lecturer (Gemini).
o	Chain-of-Thought Prompting: Asking the model to break down key points before summarising (Claude).
o	Feedback Refinement: Give further instructions on simplifying and adding examples (all models in Step 2).
5.	Output Collection:
o	Summaries from each platform (ChatGPT, Gemini, Claude, Copilot) were recorded in Step 1 and Step 2 formats.
6.	Comparison & Analysis:
o	Outputs were compared across AI models for clarity, depth, simplicity, and inclusion of real-world examples.
o	Results were presented in a comparison table(Google Drive).

## Result
https://docs.google.com/document/d/1ApgIkkXzk2VYilMvNP2BAONanVlS9Z7Y/edit?usp=sharing&ouid=115009368116115585186&rtpof=true&sd=true
