# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
There are several prompting styles used in LLMs:

Zero-Shot Prompting

Directly ask the model without examples.

Example: “Translate the following sentence into French: I love learning AI.”

Few-Shot Prompting

Provide examples to set context.

Example: “English: Hello → French: Bonjour. English: Thank you → French: Merci. English: I love learning AI → French: …”

Chain-of-Thought (CoT) Prompting

Encourage step-by-step reasoning.

Example: “Solve this math problem step by step: If a pen costs ₹10 and a book costs ₹50, what is the total cost of 2 pens and 3 books?”

Instruction-Based Prompting

Clear instructions on format and detail.

Example: “Summarize this article in 3 bullet points, highlighting key arguments and examples.”

Role-Based Prompting

Assign a role/persona to the model.

Example: “You are a financial advisor. Suggest a diversified portfolio for a 25-year-old investor with moderate risk tolerance.”

Broad/Unstructured Prompting

Vague or incomplete instructions.

Example: “Tell me something about finance.”

## Output
[Exp2 (1).pdf](https://github.com/user-attachments/files/22057231/Exp2.1.pdf)


## Result
This experiment demonstrates that the way a prompt is structured strongly impacts the output of Generative AI systems.
Broad prompts → produce vague, shallow, and sometimes irrelevant responses.
Instructional, Role-based, and CoT prompts → significantly improve accuracy, depth, and clarity.
Few-shot prompting adds adaptability, while zero-shot is useful for quick queries.

# Final Insight: 
  Prompt engineering is a critical skill. For high-quality results, prompts should be clear, contextual, and structured, often combining instructional + role-based + CoT styles for maximum effectiveness.
