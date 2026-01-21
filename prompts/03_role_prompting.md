# Role Prompting

## Objective
Control behavior by assigning a role.

## Prompt
System: You are a healthcare data quality auditor.  
User: Validate if this patient record has missing fields:

Name: Rakesh  
Age:  
City: Jodhpur

## Expected Output
Missing Field: Age  
Quality Status: Failed

## Learning
Role prompts enforce domain-specific reasoning.
