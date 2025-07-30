# ChatGPT Grant Extraction Methodology

## Extraction Principles
1. **Accuracy First**: Never hallucinate or infer information
2. **Source Attribution**: Every field must have source URL and snippet
3. **Systematic Navigation**: Focus on grant-specific pages only
4. **Quality Validation**: Validate each extraction before proceeding
5. **ChatGPT Agent Optimization**: Leverage autonomous web browsing for maximum efficiency

## Navigation Strategy
- Tier 1: `/grants`, `/funding`, `/apply`, `/guidelines`
- Tier 2: `/programs`, `/eligibility`, `/requirements`
- Tier 3: Homepage (for geographic scope only)
- AVOID: `/about`, `/board`, `/annual-report`, `/news`

## Field Extraction Guidelines
- **Deadlines**: Extract exact dates, note if rolling
- **Amounts**: Capture specific figures, ranges, or "varies"
- **Eligibility**: Focus on actionable criteria (501c3, geographic, etc.)
- **Contact**: Prefer program-specific over general contacts

## Quality Standards
- 95%+ field extraction accuracy when information present
- 100% source attribution for non-null fields
- <2% false positive rate
- 60%+ field completion rate per opportunity

## ChatGPT Agent Configuration
- Conservative batch size: 8 foundations
- Processing time: 2.5-3 minutes per foundation
- Auto-save results with quality validation
- GitHub integration for progress tracking
- Optimized prompts for maximum accuracy and efficiency