# AI Research Agentic System using Tavily and LangGraph

# Overview

This project implements an AI research agentic system designed to autonomously gather, analyze, and generate structured responses based on real-time web data. The system is built using Tavily for online information retrieval, LangGraph for workflow execution, and a Hugging Face language model for drafting responses.

# Features

- # Research Agent:

  *Uses Tavily to gather real-time web data.
  *Extracts relevant snippets and formats them for further processing.

- # Drafting Agent:

  *Utilizes a Hugging Face language model to analyze collected research data.
  *Generates a structured and informative response based on findings.

- # Workflow Execution:

  *Implemented using LangGraph to ensure seamless flow of information between agents.
  *Efficient processing pipeline for real-time or batch research tasks.

  # Architecture

  # Input:
   User provides a query or research topic.

  # Research Agent:
  -Queries Tavily to retrieve relevant web content.
  -Extracts key insights and formats data.

# Drafting Agent:
  -Processes retrieved data using a Hugging Face model.
  -Generates a well-structured response with citations and summaries.
  -Output: Returns an AI-generated research summary.
