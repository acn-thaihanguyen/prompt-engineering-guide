# Generative AI and Prompt Engineering: Basic Guide

**Author:** Nguyen Thai Ha (AI-CMT)

**For more details:** [Click here](https://github.com/acn-thaihanguyen/prompt-engineering-guide/blob/main/GenAI%20and%20Prompt%20Engineer%20Summary.pdf)

**For quick summary, please read the overview below　↓**

## Overview

This guide provides an introduction to Generative AI (Gen AI) and Prompt Engineering, highlighting fundamental concepts, applications, techniques, and future directions. It aims to equip readers with essential knowledge to understand and utilize Gen AI and prompt engineering effectively.

## Table of Contents

1. [What is Generative AI?](#what-is-generative-ai)
2. [How Gen AI Works](#how-gen-ai-works)
3. [Applications of Gen AI](#applications-of-gen-ai)
4. [What is Prompt Engineering and its Attributes](#what-is-prompt-engineering-and-its-attributes)
5. [Ineffective Prompt Example and How to Improve It](#ineffective-prompt-example-and-how-to-improve-it)
6. [Key Parameters in Prompt Engineering](#key-parameters-in-prompt-engineering)
7. [Examples of Techniques in Prompt Engineering](#examples-of-techniques-in-prompt-engineering)
8. [Challenges in Prompt Engineering](#challenges-in-prompt-engineering)
9. [Future Directions](#future-directions)
10. [Conclusion](#conclusion)
11. [References](#references)

## What is Generative AI?

Generative AI is a field of artificial intelligence focused on creating new content, including text, images, audio, video, and code, using deep learning models.

## How Gen AI Works

Gen AI operates based on deep learning models, particularly Transformer models. The training process involves collecting large datasets, supervised learning, and content generation through prediction.

## Applications of Gen AI

- **Content creation**: Writing articles, creating images, composing music.
- **Software coding assistance**: Suggesting and auto-writing programming code.
- **Chatbot performance improvement**: Virtual assistants, chatbots.
- **Content classification**: Categorizing and organizing content.
- **Question Answering and Discovery**: Providing answers and discovering relevant information.
- **Summarization**: Condensing large amounts of information.
- **Simplification**: Making complex information easier to understand.
- **Tone Manipulation**: Adjusting the tone of written content.

## What is Prompt Engineering and its Attributes

* Prompt Engineering involves designing and optimizing prompts to ensure AI models respond accurately.
* Key elements include clarity, context, detail, specific format, audience, content domain, perspective, tone, and role specification.

### Ineffective Prompt Example and How to Improve It

#### Ineffective Prompt:
- "What are semiconductors and how are they used in the electronics industry?"

#### Improved Prompt:
- "You are `an expert` in semiconductors. `Explain to elementary school students` what semiconductors are and how they are used in the electronics industry."

## Key Parameters in Prompt Engineering

- **Temperature**: Controls result randomness.
- **Top_p**: Selects top words for generating content.
- **Max Length**: Limits output length.
- **Stop Sequences**: Defines stop points in generation.
- **Frequency Penalty**: Reduces word repetition.
- **Presence Penalty**: Diversifies word usage.

## Common techniques in Prompt Engineering

1. **Zero-Shot Prompting**: No specific examples needed.
2. **Few-Shot Prompting**: Uses specific examples for better performance.
3. **Chain-of-Thought Prompting**: Generates intermediate steps for complex tasks.
4. **Self-Consistency**: Selects the most consistent answer from multiple responses.
5. **Generated Knowledge Prompting**: Uses generated knowledge for responses.
6. **Automatic Prompt Engineer (APE)**: Automates prompt creation and evaluation.

### Examples of Techniques in Prompt Engineering

- **Zero-Shot Prompting**: "Translate the following English sentence to French: 'The cat is on the roof.’"
- **Few-Shot Prompting**: "Translate the following sentences to French: 'The cat is on the roof.' -> 'Le chat est sur le toit.' Now translate: 'The bird is in the cage.'"
- **Chain-of-Thought Prompting**: "To solve the math problem 24 + 18, first add 20 to 24 to get 44, then add 2 + 18 to get 20. Finally, add 44 and 20 to get 64."

## Challenges in Prompt Engineering

1. **Ambiguity in Prompts**: Clearer guidelines needed.
2. **Model Limitations**: Continuous improvement required.
3. **Ethical Considerations**: Ensuring unbiased and ethical content.
4. **Scalability**: Developing automated tools for large-scale applications.

## Future Directions

1. **Large Multi-Models**: Integrating multiple models for diverse content generation.
2. **Small Language Models (SLMs)**: Optimizing large models for efficiency.
3. **Retrieval Augmented Generation (RAG)**: Enhancing models with external knowledge.
4. **AI on Edge Devices**: Developing efficient AI models for real-time processing on devices.

## Conclusion

Generative AI and prompt engineering are transformative fields with significant potential and challenges. Continuous innovation and ethical focus are crucial for advancing these technologies.

## References
1. [Prompting Guide](https://www.promptingguide.ai/jp)
2. [OpenAI Best Practices](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-the-openai-api)
3. “Principled Instructions Are All You Need for Questioning LLaMA-1/2, GPT-3.5/4” Bsharat et al., 2024.
