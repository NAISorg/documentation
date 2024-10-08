---
hidden: true
---

# AI & Data Privacy

Market View uses OpenAI to generate the insights we show you about your data on the [Comparisons page](https://marketview.nais.org/comparisons).

## Overview

To add AI Insights to your Comparisons, Market View sends [25 of your DASL datapoints](https://docs.marketview.nais.org/nais/comparisons/data-used-in-comparisons) related to financial aid. We are not sending any of your data with words in it, no school names, other names, etc. Only a select list of numbers are shared temporarily with OpenAI to generate insights.&#x20;

We are using OpenAI's API. We are not using ChatGPT.  We send OpenAI a list of numbers and ask it to generate an insight, which we then display on the screen to you.

**OpenAI does not use your data to train their models.** From OpenAI: [We do not train our models on your business data by default.](#user-content-fn-1)[^1] [Unless they explicitly opt-in, organizations are opted out of data-sharing by default](#user-content-fn-2)[^2].

OpenAI temporarily stores your data on their servers for 30 days. This is standard practice for web services so they can have a paper trail to protect against nefarious use. From OpenAI: [OpenAI may securely retain API inputs and outputs for up to 30 days to identify abuse.](#user-content-fn-3)[^3]

[Read more at OpenAI's Enterprise privacy document.](https://openai.com/enterprise-privacy/) Please note that this is different than their ChatGPT offering, ChatGPT is much less private.

## Q\&A

Which subprocessor(s) is/are being used to produce AI-generated completions?

* [OpenAI uses this list of subprocessors. ](https://platform.openai.com/subprocessors/openai-subprocessor-list)

Which AI language models are being used?

* [GPT-4o mini](https://platform.openai.com/docs/models/gpt-4o-mini)

Is the AI in question based on machine learning algorithms or large language models?

* Yes, LLM.

Is user data either user related PII or otherwise uploaded data being used to train the AI model?

* No

Is data being used to improve the product via AI?

* No

What explainability measures (if any) are used in understanding the output of the AI model?

* We're prompting the LLM to make the response easy to understand, and providing users the data used so they can understand and analyze the AI responses.

How long is data retained? Where? Is any data such as prompts cached for performance?

* OpenAI retains the data for 30 days, then deletes it.

What steps (if any) have been implemented to reduce bias in AI generated output?

* Since this is a very small set of anonymous numeric financial data, there is no concern about biased output.

[^1]: [https://openai.com/enterprise-privacy/](https://openai.com/enterprise-privacy/)

[^2]: [https://help.openai.com/en/articles/5722486-how-your-data-is-used-to-improve-model-performance](https://help.openai.com/en/articles/5722486-how-your-data-is-used-to-improve-model-performance)

[^3]: [https://openai.com/enterprise-privacy/](https://openai.com/enterprise-privacy/)
