# Few-Shot Prompting

## Objective
Improve accuracy using examples.

## Prompt
Example 1:
Input: Rahul is 25 and lives in Delhi  
Output:
{"name":"Rahul","age":25,"city":"Delhi"}

Example 2:
Input: Neha is 29 from Pune  
Output:
{"name":"Neha","age":29,"city":"Pune"}

Now extract:
"Amit is 34 and lives in Jaipur"

## Expected Output
{"name":"Amit","age":34,"city":"Jaipur"}

## Learning
Few-shot improves consistency and reduces hallucination.
