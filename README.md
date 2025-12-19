# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Date:19-12-25
# Register no.25013745
# Aim: Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools

# AI Tools Required:
chatgpt,copilot,gemini

# Code:
```
import requests

# Persona-based prompt
prompt = """
Act as an experienced healthcare data analyst.

Explain how AI can be used for early disease detection in hospitals
and provide a brief example.
"""

# Function to simulate API call
def call_ai_tool(tool_name):
    print(f"\n--- Response from {tool_name} ---")

    if tool_name == "ChatGPT":
        return "AI analyzes patient health records and lab reports to predict diseases early, improving treatment outcomes."

    elif tool_name == "Gemini":
        return "Early disease detection uses AI models on medical data to identify risk patterns before symptoms appear."

    elif tool_name == "Copilot":
        return "AI supports doctors by analyzing patient data to flag potential health risks in advance."

    else:
        return "Tool not supported."

# List of AI tools
ai_tools = ["ChatGPT", "Gemini", "Copilot"]

# Collect and display responses
responses = {}

for tool in ai_tools:
    responses[tool] = call_ai_tool(tool)
    print(responses[tool])

# Simple comparison insight
print("\n--- Comparative Insight ---")

for tool, response in responses.items():
    print(f"{tool}: Response Length = {len(response)} characters")
```


# Explanation:
Experiment the persona pattern as a programmer for any specific applications related with your interesting area. 
Generate the outoput using more than one AI tool and based on the code generation analyse and discussing that. 

# Conclusion:
[Exp6 (1).docx](https://github.com/user-attachments/files/24262591/Exp6.1.docx)


# Result: The corresponding Prompt is executed successfully.
