# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This repository is designed for generating comprehensive Statement of Work (SOW) documentation from meeting transcripts. It contains a sophisticated prompt engineering system for analyzing business meetings and extracting structured project requirements.

## Architecture Overview

The repository follows a simple but effective structure:

- **`prompts/SOW Prompt`** - Contains the master prompt template for SOW generation. This is a comprehensive XML-structured prompt that instructs an AI to analyze meeting transcriptions and produce detailed SOW documentation following business best practices.

- **`examples/`** - Contains sample SOW documents and reference materials (e.g., `AsSent_SOW_Aubuchon_001.docx`)

- **`transcripts/`** - Directory for storing meeting transcripts that will be processed using the SOW prompt

- **`prompts/SOW_request.md`** - Currently empty but intended for SOW request documentation

## Key Components

### SOW Prompt Structure
The main prompt (`prompts/SOW Prompt`) is a sophisticated XML template that includes:
- Detailed instructions for extracting business requirements from transcripts
- SOW best practices and documentation standards  
- A comprehensive output structure template covering all aspects of project documentation
- Reasoning guidance for thorough analysis

### Documentation Standards
The prompt enforces professional SOW documentation including:
- Executive summaries with strategic alignment
- Comprehensive stakeholder identification
- Detailed scope definition (inclusions/exclusions/assumptions)
- Functional and non-functional requirements
- Deliverables with acceptance criteria
- Risk assessment and mitigation strategies
- Timeline and resource planning

## Working with This Repository

When processing meeting transcripts:
1. Place transcript files in the `transcripts/` directory
2. Use the SOW prompt template with transcript content
3. Generated SOWs should follow the structured format defined in the prompt
4. Reference examples in the `examples/` directory for formatting guidance

The prompt is designed to produce markdown-formatted SOW documents with timestamp citations and comprehensive business analysis.