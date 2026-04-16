AI Code Review Assistant
Automated code review powered by Amazon Bedrock and Generative AI.
Overview
A multi-agent AI pipeline that reviews code for bugs, security vulnerabilities, and quality issues — then generates a fixed version of the code.
Agents
AgentWhat it doesLanguage DetectorIdentifies programming language and complexityBug FinderDetects logic errors and edge casesSecurity AnalyzerFinds SQL injection, hardcoded secrets, OWASP issuesCode Quality ReviewerScores readability and maintainability (1-10)Fix SuggesterGenerates corrected version of the code
Tech Stack

Amazon Bedrock — Claude 3 Sonnet (foundation model)
Python — boto3, Jupyter Notebook
AWS — us-east-1

How to Run

Open the notebook in Google Colab or Jupyter
Run cells top to bottom
No AWS needed — run Cell 10 (Mock Demo) for a full simulation
