# ChatGPT Custom Instructions

A collection of optimized custom instructions that measurably improve ChatGPT performance.

![MMLU Performance Results](mmlu.png)

## About

This repository contains battle-tested custom instructions for ChatGPT that enhance performance on complex tasks. Instructions were rigorously tested against the MMLU (Massive Multitask Language Understanding) benchmark, showing a significant performance improvement.

## Custom Instructions

- [High-Stakes Expert Reasoner](High-Stakes-Expert-Reasoner.md) - Optimizes for detailed expert-level responses with concrete reasoning.
- [Clarity-First Response Protocol](Clarity-First-Response-Protocol.md) - Focuses on clear, concise communication with structured information.

## Performance Testing

I invested ~$150 to test these instructions against the complete MMLU benchmark - a comprehensive test evaluating language models across mathematics, history, physics, medicine, law, and other domains. MMLU measures how well LLMs process information at college and professional levels.

Testing was conducted across **all MMLU categories**, encompassing approximately **14,000 tasks** in total. Instructions were evaluated using [Factly](https://factly.readthedocs.io) - a modern CLI tool for assessing LLM factuality. Results demonstrated:

- **Baseline (No Custom Prompt)**: 82.82% factuality
- **High-Stakes Expert Reasoner**: 83.17% factuality (+0.35%)
- **Clarity-First Response Protocol**: 83.44% factuality (+0.62%)

These results demonstrate meaningful improvements in GPT-4o's factual accuracy across elementary to college-level mathematics, abstract algebra, physics, and 52+ additional subject areas.

I will continue performance evaluation with new models and prompts, publishing all updates to this repository as they become available.

## Usage

1. Go to ChatGPT
2. Navigate to Settings
3. Select Personalization
4. Enter these instructions in Custom Instructions


## Compatibility

- Works with ChatGPT voice mode
- Tested with GPT-4o, GPT-4o-mini, GPT-4.1, GPT-4.1-mini, GPT-4.1-nano
- Compatible with latest ChatGPT interfaces

## License

Released into the public domain - see [LICENSE](LICENSE) for details.
