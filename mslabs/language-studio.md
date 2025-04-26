# Azure Language Studio Lab: Sentiment Analysis

## Overview
This document outlines my experience working with Azure AI Language Studio to analyze text sentiment in hotel reviews. Natural Language Processing (NLP) is a powerful branch of AI that deals with understanding and processing written language, which has numerous applications in business intelligence and customer experience analysis.

## Technology Overview
Azure AI Language Service provides text analysis and NLP capabilities including sentiment analysis, key phrase extraction, and language detection. These services allow organizations to gain valuable insights from customer feedback, social media, and other textual data sources.

## Lab Environment
For this exercise, I created an Azure Language resource with the following specifications:
- **Resource Type**: Language service
- **Region**: East US 2
- **Pricing Tier**: Free F0
- **Managed Identity**: Enabled

## Sentiment Analysis Experiment

### Methodology
I tested Azure's sentiment analysis capabilities by analyzing three different hotel reviews:
1. A negative review of an old hotel with poor service
2. A positive review of a hotel with good amenities and staff
3. A mixed review containing both positive and negative sentiments

### Test Case 1: Negative Review Analysis
**Input**: Review of "Tired hotel with poor service" at The Royal Hotel, London
**Findings**: 
- The system correctly identified the overall negative sentiment
- Each sentence was individually analyzed for sentiment
- Confidence scores were provided for positive, neutral, and negative classifications

### Test Case 2: Positive Review Analysis
**Input**: Review of "Good Hotel and staff" at The Royal Hotel, London
**Findings**:
- The system accurately detected the positive sentiment
- High confidence scores aligned with the positive language used
- Sentiment was consistent across sentences

### Test Case 3: Mixed Sentiment Analysis
**Input**: Review of "Very noisy and rooms are tiny" at The Lombard Hotel, San Francisco
**Findings**:
- The system successfully identified the mixed nature of the review
- Sentence-level analysis showed transitions between negative and neutral sentiments
- Confidence scoring reflected the nuanced content

## Key Learnings
Through this lab, I gained practical experience with:
1. Setting up Azure AI Language resources
2. Understanding the capabilities of sentiment analysis
3. Interpreting confidence scores in AI language analysis
4. Recognizing how AI can process nuanced human expression
5. Identifying potential business applications for sentiment analysis

## Business Applications
This technology could be valuable for:
- Customer feedback analysis for hotels and service industries
- Brand reputation monitoring
- Product review assessment
- Customer service improvement

## Screenshots
![Language Studio Interface](./images/language-studio-interface.png)
![Negative Review Analysis](./images/negative-review-analysis.png)
![Positive Review Analysis](./images/positive-review-analysis.png)
![Mixed Review Analysis](./images/mixed-review-analysis.png)

---

*Completed as part of AI 900 Lab 3 on the MSLE Skillable Platform for the AI Applications course (ITAI 2372).*
