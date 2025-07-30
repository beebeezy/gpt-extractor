# GPT Extractor - ChatGPT Grant Extraction System

## Overview
ChatGPT Agent-powered grant opportunity extraction system for the Grantegy platform. This repository tracks extraction batches, quality metrics, and processed grant data using ChatGPT's autonomous web browsing capabilities.

## Directory Structure
- `raw_extractions/` - Raw NDJSON output from ChatGPT extraction batches
- `processed_data/` - Validated and cleaned grant records
- `quality_reports/` - Accuracy metrics and batch analysis
- `foundation_urls/` - Input URL lists organized by batch
- `documentation/` - Extraction guidelines and methodology
- `scripts/` - Data processing and validation utilities
- `templates/` - JSON schema templates and examples

## Workflow
1. Add foundation URLs to `foundation_urls/batch_XXX_urls.txt`
2. Run ChatGPT Agent extraction process with optimized prompts
3. Raw results saved to `raw_extractions/batch_XXX.ndjson`
4. Quality report generated in `quality_reports/batch_XXX_report.json`
5. Validated data processed to `processed_data/`

## Quality Metrics
- Target accuracy: 95%+ field extraction
- Source attribution: 100% for all non-null fields
- Processing rate: 8 foundations per batch (conservative start)
- ChatGPT Agent Mode optimization for maximum throughput

## Current Status
- Batch processing: READY
- Quality tracking: ENABLED
- GitHub integration: ACTIVE
- ChatGPT Agent: CONFIGURED