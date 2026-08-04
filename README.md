# Learning AI Through Real Projects 

## Project 01 - CDB Investments with NotebookLM

Status: Work in Progress

### 🎯 Context and Objectives

This project was developed as part of an AI learning challenge, which required the creation of a thematic NotebookLM notebook based on an introductory financial topic.

Certificates of Deposit (CDBs) were chosen because they provide an accessible and well-documented investment topic, making them an excellent starting point for AI-assisted learning. In addition, the availability of reliable online resources allows information to be effectively collected, compared, and organized.

The primary objective of this project is to apply the knowledge acquired throughout the AI training program by using NotebookLM to build a structured learning resource. It also aims to explain how CDB investments work, compare them with other investment options, and identify the most suitable alternatives for different investor profiles.

Beyond understanding CDB investments, this project also explores how NotebookLM can support active learning through source curation, structured summaries, prompt engineering, and knowledge organization.

This repository documents the entire learning process, from source selection to prompt refinement and the final study guide.

### 📚 Source Curation

The quality of an AI-assisted study depends directly on the quality of its reference materials. For this reason, the sources selected for this project were chosen based on their credibility, accessibility, and relevance to introductory CDB investments. Together, they provide complementary perspectives that support a comprehensive understanding of the topic and serve as the knowledge base for all NotebookLM interactions.

| Source | Description |
|--------|-------------|
| **BTG Pactual** | Introduction to CDBs, including key concepts, security, and investment fundamentals. [Access the article](https://content.btgpactual.com/blog/investimentos/o-que-e-cdb) |
| **XP Investimentos** | Comprehensive guide explaining how CDBs work and when to invest. [Access the article](https://conteudos.xpi.com.br/aprenda-a-investir/relatorios/cdb/) |
| **Wise** | Comparison of CDB investment options and banking institutions. [Access the article](https://wise.com/br/blog/investir-em-cdb) |
| **InfoMoney** | Detailed guide covering profitability, liquidity, taxation, and investment strategies. [Access the article](https://www.infomoney.com.br/guias/cdb/) |
| **InvestNews** | Investment simulator used to compare CDB scenarios. [Open the simulator](https://investnews.com.br/ferramentas/simuladores/simulador-de-investimento/) |

These sources were intentionally selected to combine educational content from financial institutions, independent financial media, and a practical investment simulator. This combination enabled not only a better understanding of CDB investments but also the validation and comparison of information across different perspectives.

### 🤖 Prompt Engineering

This project explored how prompt design influences the quality of AI-generated responses. Rather than asking isolated questions, the prompts were progressively refined to obtain clearer explanations, better structured summaries, and more reliable references. This iterative process helped demonstrate how effective prompt engineering can improve both learning outcomes and knowledge organization.

#### Strategy

Instead of starting with highly detailed prompts, the experiment began with simple, introductory questions to establish a baseline response. Each prompt was then refined individually by applying different prompt engineering techniques, allowing the responses to be compared in terms of clarity, structure, and usefulness. This approach made it possible to evaluate how small changes in prompt design affected the quality of the generated content.

#### Experiment 1 – Understanding CDB

<h1 style="color: #0076FF;">1. Initial Prompt</h1>

**Technique:** Baseline Prompt

**Prompt**
```text
What is CDB and how can I invest?
```

**Response Summary**

NotebookLM explained the concept of a CDB as a fixed-income investment issued by banks, described the investment process, and introduced key concepts such as profitability, liquidity, taxation, and FGC protection.

**Key References**

- BTG Pactual
- XP Investimentos
- InfoMoney

**Observation**

The response was comprehensive but relatively long for quick review.

#### Prompt Refinement

**Technique:** Output Formatting + Instruction Prompting

**Prompt**
```text
What is a CDB and how do I invest in it? Please provide a clear explanation and a step-by-step flowchart to illustrate the process.
```
**Response Summary**

The response preserved the same technical information while presenting the investment process in a sequential and easier-to-follow structure.

**Improvement**

- Better organization
- Easier readability
- More suitable for beginners

#### Final Refinement

**Technique:** Guardrails

**Prompt**
```text
> Please rewrite the answer to make it simpler and more concise.
```

**Response Summary**

The generated answer became considerably shorter while preserving the essential concepts regarding investment steps, profitability, taxation, and safety.

**Improvement**

- Reduced verbosity
- Faster review
- Better suited for study notes
