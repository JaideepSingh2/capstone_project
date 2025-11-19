# Job Application Assistant

## Overview

This tool helps with job applications by comparing a resume to a job description. It then creates a personalized cover letter, points out any skill gaps, and generates practice interview questions.

**Input:** Resume (PDF/as location ) + Job description (as text)

**Output:** PDF report with tailored cover letter, skill gap analysis, interview preparation questions

## Reason for Picking This Project

This project puts into practice several key topics from the MAT496 course. We use custom prompts to understand resumes, analyze job descriptions, and write cover letters. To keep our data organized, we use Pydantic models. The project uses semantic search to find not just exact skill matches, but also related skills. We use RAG to pull information from the resume to write personalized cover letters. It also uses external tools to research companies. The whole process is managed by LangGraph, which connects all the steps, handles different conditions, and even allows for a person to review the results.

## Plan

- [Done] Step 1: Set up project structure and dependencies
- [Done] Step 2: Define Pydantic data models for structured output
- [Done] Step 3: Implement resume parser node with prompting
- [TODO] Step 4: Implement job description analyzer node
- [TODO] Step 5: Implement company research node with Tavily tool calling
- [TODO] Step 6: Implement skill gap analyzer with semantic matching
- [TODO] Step 7: Implement cover letter generator with RAG
- [TODO] Step 8: Implement interview question generator
- [TODO] Step 9: Build LangGraph with state, nodes, and conditional edges
- [TODO] Step 10: Add human-in-the-loop checkpoint
- [TODO] Step 11: Test with sample inputs and refine
- [TODO] Step 12: Record demo video
