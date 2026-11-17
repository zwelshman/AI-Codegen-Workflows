# AI-Codegen-Workflows

## Problem Statement
A key usecase for LLMs is to generate code. 
The challange, as i see it, is initiating a request from a system that returns the code
you will use first time. Admittedly, i will nearly always tweak something from the generated output 
and once code has been generated i will want the system to explain the code line by line. 
There are some things that work better than others and there maybe combinations or ways that yield better results

## AI models without a dedicated harness or context
In this repository, i will explore code generation options for:
- Different AI models
-- Explore capabilities that have been integrated into more recent models

## AI models with no harness, but more context
- Adding the context of a GitHub repository
-- Including the GitHub Repository in the AI model's context - RepoMix

## Retrival Augmented Generation (RAG)
-- chunking with AST, chunk size and overlap
-- embedding models
-- Semantic Search 
-- Keyword Search
-- reranking

## Agentic Approaches that i've found helpful with a harness.
- In an Agent.md file , or equivalent.
-- Define your files and folders 
-- Tell the model where it will find answers to which types of questions
-- Hard rules
-- Skills - filesystem - let the Agent find it
-- Tools 
-- MCP servers

