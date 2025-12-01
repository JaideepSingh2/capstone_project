# Job Application Assistant

## Overview

This tool helps with job applications by comparing a resume to a job description. It then creates a personalized cover letter, points out any skill gaps, and generates practice interview questions.

**Input:** Resume (PDF/as location ) + Job description (as text)

**Output:** PDF report with tailored cover letter, skill gap analysis, interview preparation questions

## Reason for Picking This Project

I am in my final year and was preparing for job placements, so I needed a tool to speed up resume review, cover letter writing, and interview preparation. Building an assistant like this felt directly useful and would save a lot of time during the application process.
This project puts into practice several key topics from the MAT496 course. We use custom prompts to understand resumes, analyze job descriptions, and write cover letters. To keep our data organized, we use Pydantic models. The project uses semantic search to find not just exact skill matches, but also related skills. We use RAG to pull information from the resume to write personalized cover letters. It also uses external tools to research companies. The whole process is managed by LangGraph, which connects all the steps, handles different conditions, and even allows for a person to review the results.

## Plan

- [Done] Step 1: Set up project structure and dependencies
- [Done] Step 2: Define Pydantic data models for structured output
- [Done] Step 3: Implement resume parser node with prompting
- [Done] Step 4: Implement job description analyzer node
- [Done] Step 5: Implement company research node with Tavily tool calling
- [Done] Step 6: Implement skill gap analyzer with semantic matching
- [Done] Step 7: Implement cover letter generator with RAG
- [Done] Step 8: Implement interview question generator
- [Done] Step 9: Build LangGraph with state, nodes, and conditional edges
- [Done] Step 10: Add human-in-the-loop checkpoint
- [Done] Step 11: Test with sample inputs and refine
- [Done] Step 12: Record demo video

Link: ![Google_Drive](https://drive.google.com/file/d/14_qMiDv-plSRUZ_MAeyaeA-uUCX6eoBk/view?usp=sharing)

## Conclusion

The project has been completed satisfactorily. It successfully automates the time-consuming aspects of the job application process, such as analyzing job descriptions and generating tailored cover letters. The integration of LangGraph and RAG proved effective in creating a coherent and useful assistant, fulfilling the initial goal of saving time during placement preparation. It was rewarding to see a real problem getting solved that I was facing.
