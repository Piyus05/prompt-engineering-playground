# Zero-Shot Prompting

## Objective
Convert unstructured text into structured JSON without examples.

## Prompt
System: You are a data extraction assistant.  
User: Extract name, age, city from this sentence:

"Amit Sharma, 32 years old, lives in Jaipur."

## Expected Output
{
  "name": "Amit Sharma",
  "age": 32,
  "city": "Jaipur"
}

## Learning
Zero-shot prompts work well for simple extraction but may fail for complex text.
