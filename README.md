# AI Code Review Assistant
Automated code review powered by Amazon Bedrock and Generative AI.

## Overview
A multi-agent AI pipeline that reviews code for bugs, security vulnerabilities, and quality issues — then generates a fixed version of the code.

## Agents
| Agent | What it does |
|---|---|
| Language Detector | Identifies programming language and complexity |
| Bug Finder | Detects logic errors and edge cases |
| Security Analyzer | Finds SQL injection, hardcoded secrets, OWASP issues |
| Code Quality Reviewer | Scores readability and maintainability (1-10) |
| Fix Suggester | Generates corrected version of the code |

## Tech Stack
- **Amazon Bedrock** — Claude 3 Sonnet (foundation model)
- **Python** — boto3, Jupyter Notebook
- **AWS** — us-east-1

## How to Run
1. Open the notebook in Google Colab or Jupyter
2. Run cells top to bottom
3. **No AWS needed** — run Cell 10 (Mock Demo) for a full simulation

## Project Type
Personal demonstration project — IBM Generative & Agentic AI Developer Badge
