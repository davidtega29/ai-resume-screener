# AI Resume Screener

An AI-powered resume screening and candidate evaluation workflow built with n8n and OpenAI.

## Overview

This workflow automates the initial screening of job candidates by analyzing resume information, evaluating the candidate against predefined criteria, generating a structured assessment, and routing the candidate based on their overall score.

## Workflow

1. Resume information is provided to the workflow.
2. An AI Agent analyzes the resume.
3. OpenAI evaluates the candidate based on skills, experience, education, communication, and overall fit.
4. A Structured Output Parser formats the AI response.
5. The candidate receives an overall score from 0–100.
6. Conditional logic routes the candidate based on their score.

## Tools Used

- n8n
- OpenAI
- AI Agent
- Structured Output Parser
- Switch / conditional logic
- JSON

## Key Features

- AI-powered candidate evaluation
- Structured AI output
- Candidate scoring
- Automated decision routing
- Workflow-based business process automation

## Output

The workflow generates:

- Candidate name
- Job title
- Overall score
- Decision
- Summary
- Strengths
- Weaknesses
- Recommendation

## Purpose

This project demonstrates how AI and workflow automation can be used to streamline repetitive candidate screening tasks and support recruitment workflows.

## Project Status

Prototype / learning project.

## Workflow Screenshot

![AI Resume Screener Workflow](workflow.png)
