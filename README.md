#  EXP-2: Prompt Engineering

##  Aim
To perform a **comparative analysis** of different types of prompting patterns and evaluate their effectiveness across various test scenarios. This includes testing how models respond to **broad or unstructured prompts** versus **basic, clearer, and refined prompts**, analyzing the **quality**, **accuracy**, and **depth** of the generated responses.

---

##  Experiment
The experiment involves:

- Testing a language model (e.g., ChatGPT) with multiple **prompting styles**:
  - Zero-shot
  - One-shot
  - Few-shot
  - Chain-of-Thought
  - Refined Prompting
  - Broad Prompting

- Running these prompt types across **diverse scenarios** like:
  - Math reasoning
  - Story generation
  - Code generation
  - Text summarization
  - General knowledge/factual queries

- **Evaluating** each output based on:
  - Relevance
  - Accuracy
  - Clarity
  - Creativity (if applicable)
  - Depth of reasoning

---

##  Algorithm / Procedure

1. **Define Prompting Types**  
   Choose different prompting styles: Zero-shot, One-shot, Few-shot, etc.

2. **Select Test Scenarios**  
   Prepare multiple task types for testing (e.g., logic, writing, summarization).

3. **Design Prompt Variants**  
   For each scenario, create:
   - A broad/unstructured prompt
   - A refined/specific prompt
   - A few-shot or chain-of-thought variant if applicable

4. **Run Model Interactions**  
   Input each prompt into the model and collect outputs.

5. **Evaluate Responses**  
   Score and analyze the responses using pre-defined metrics.

6. **Compare Results**  
   Tabulate and interpret the strengths/weaknesses of each prompting pattern.

---

##  Output

###  Sample Comparison Table

| Scenario       | Prompt Type        | Prompt Example                                      | Output Quality | Observations                                |
|----------------|--------------------|-----------------------------------------------------|----------------|---------------------------------------------|
| Math Problem    | Zero-shot          | `What is 27 × 43?`                                  | Moderate       | Answered correctly, no explanation          |
| Math Problem    | Chain-of-Thought   | `Let's solve step by step: What is 27 × 43?`        | High           | Gave correct answer with detailed reasoning |
| Story Writing   | Broad Prompt       | `Write a story.`                                    | Variable       | Creative but lacked structure               |
| Story Writing   | Refined Prompt     | `Write a 100-word story about a robot who dreams.`  | High           | Focused, imaginative, and concise           |
| Coding Task     | Few-shot Prompting | Code examples + `Write a Python program for XYZ.`   | High           | Accurate and well-structured code           |
| Summarization   | Zero-shot          | `Summarize the following paragraph.`                | Moderate       | Missed some key points                      |
| Summarization   | Refined Prompt     | `Summarize the key points in 2 sentences.`          | High           | Clear and concise summary                   |

---

##  Result

- **Chain-of-thought prompting** improves reasoning and logical accuracy.
- **Few-shot prompting** helps in technical tasks like coding by guiding structure.
- **Refined prompts** lead to higher clarity, precision, and relevance.
- **Broad prompts** are more variable — good for creativity but less reliable.
- **Zero-shot** is efficient for simple tasks but struggles with complexity.

---

##  Conclusion

- Use **Refined/Specific prompts** for structured, focused answers.
- Use **Chain-of-Thought** for complex or multi-step reasoning tasks.
- Use **Few-shot** prompting when pattern recognition is required (e.g., code).
- Avoid overly **Broad prompts** unless open-ended or creative output is desired.

---
