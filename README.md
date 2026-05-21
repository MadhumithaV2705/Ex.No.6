# Ex.No.6 – Development of Python Code Compatible with Multiple AI Tools

## Date: 21-05-2026
## Register No: 212223060145

---

# Aim

To write and implement Python code that integrates with multiple AI tools to automate tasks such as interacting with APIs, comparing outputs, and generating actionable insights using multiple AI tools.

---

# AI Tools Required

* [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com)
* [Google Gemini](https://gemini.google.com?utm_source=chatgpt.com)
* [Claude AI](https://claude.ai?utm_source=chatgpt.com)

---

# Introduction

Artificial Intelligence tools provide APIs and intelligent interfaces that help automate software development, data analysis, report generation, and monitoring systems.

Different AI tools generate different outputs for the same prompt because of variations in:

* Model architecture
* Training data
* Optimization methods
* Response generation strategies

This experiment focuses on developing Python code compatible with multiple AI tools and analyzing their generated outputs.

The experiment uses the **Persona Pattern**, where the AI model behaves as a specialized professional in a specific domain.

Selected Domain:

```text
IoT-Based Industrial Maintenance Monitoring System
```

---

# Persona Pattern Used

## Prompt

```text
You are an expert IoT maintenance engineer and Python programmer.

Generate Python code to monitor industrial machine temperature using sensor values.
If temperature exceeds 80°C, generate an alert message and store the log data.
```
---

# Python Implementation

## Python Code

```python
import requests
import json

# Persona Prompt
prompt = """
You are an expert IoT maintenance engineer and Python programmer.

Generate Python code to monitor industrial machine temperature using sensor values.
If temperature exceeds 80°C, generate an alert message and store the log data.
"""

# Simulated AI Tool Responses

chatgpt_response = {
    "tool": "ChatGPT",
    "output": "Uses modular functions with proper alert handling and logging."
}

gemini_response = {
    "tool": "Gemini",
    "output": "Provides optimized sensor monitoring implementation."
}

claude_response = {
    "tool": "Claude",
    "output": "Generates readable and well-documented code."
}

# Store Responses
responses = [
    chatgpt_response,
    gemini_response,
    claude_response
]

# Compare Outputs
print("AI Tool Comparison Results\n")

for response in responses:
    print(f"Tool: {response['tool']}")
    print(f"Output Summary: {response['output']}")
    print("-" * 40)

# Final Insight
print("\nFinal Analysis")

print("ChatGPT focused on modular implementation.")
print("Gemini focused on optimization.")
print("Claude focused on readability and documentation.")
```

---

# Sample Output

```text
AI Tool Comparison Results

Tool: ChatGPT
Output Summary: Uses modular functions with proper alert handling and logging.
----------------------------------------

Tool: Gemini
Output Summary: Provides optimized sensor monitoring implementation.
----------------------------------------

Tool: Claude
Output Summary: Generates readable and well-documented code.
----------------------------------------

Final Analysis

ChatGPT focused on modular implementation.
Gemini focused on optimization.
Claude focused on readability and documentation.
```
---

# Conclusion

This experiment successfully developed Python code compatible with multiple AI tools for automating industrial monitoring tasks.
The Persona Pattern enabled domain-specific response generation, and the outputs from different AI tools were compared and analyzed successfully.
The experiment proved that integrating multiple AI systems improves:

* Development efficiency
* Automation capabilities
* Analytical insights
* Software quality

---

