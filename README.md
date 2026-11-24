# Research and Technical Write-ups

This repository is for independent study notes on software, data, and AI. The write-ups explain how an approach works, show how to try it on a small example, and identify which results can be reproduced.

## Featured study

### Building a Text-to-SQL Agent with Gemini 4 Neon

Khalid Abdelaty’s DataCamp tutorial follows a Python agent that answers questions about a fictional learning platform using SQLite. The key challenge is to change the definition of learner activation from course enrollment to lesson completion while keeping the same learners and seven-day window. [Original DataCamp tutorial](https://app.datacamp.com/learn/tutorials/gemini-4-neon-api-tutorial-build-a-text-to-sql-agent-in-python)

- **Follow the workflow.** Gemini proposes a SQL query, Python runs it against a read-only database, and the agent uses the returned rows to answer the question.
- **Check the metric.** Compare the original and revised results to see whether the query preserved the eligible population and counted each learner once.
- **Replay the example.** The author’s project includes a synthetic database and a recorded run you can inspect in Streamlit without a Gemini API key. [Project code and replay instructions](https://github.com/KhalidAbdelaty/gemini-4-neon-text-to-sql-agent#run-it)

## Use and attribution

These independent write-ups are intended for personal study and non-commercial use only. The original tutorials, code, and datasets are credited to their respective authors.
