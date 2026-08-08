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

#### 📌 Initial Prompt

**Technique:** 
```text
Baseline Prompt
```
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

#### 🔄 Prompt Refinement

**Technique:** 
```text
Output Formatting + Instruction Prompting
```
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

#### 🛡️ Final Refinement

**Technique:** 
```text 
Guardrails
```
**Prompt**
```text
Please rewrite the answer to make it simpler and more concise.
```

**Response Summary**

The generated answer became considerably shorter while preserving the essential concepts regarding investment steps, profitability, taxation, and safety.

**Improvement**

- Reduced verbosity
- Faster review
- Better suited for study notes

#### Experiment 2 – Advantages of Investing in CDB

#### 📌 Initial Prompt

**Technique:** 
```text
Baseline Prompt
```
**Prompt**
```text
Explain to me the advantages of investing in CDB.
```

**Response Summary**

The initial response identified the main advantages of investing in CDBs, including higher profitability than savings accounts, FGC protection, accessibility, liquidity, different remuneration models, tax efficiency, and ease of investing. Although comprehensive, the explanation was relatively long and presented the information in a way that could be simplified for beginner-level study.

**Observation**

The response answered the question correctly but contained more detail than necessary for a quick review.

#### 🔄 Prompt Refinement

**Technique:** 
```text
Output Formatting
```
**Prompt**
```text
Explain the advantages of investing in a CDB. Present the answer as a comparison table with the columns: Advantage, Explanation, and Practical Example.
```

**Response Summary**

The response was transformed into a well-organized comparison table, categorizing each advantage of investing in a CDB alongside a brief explanation and a practical example. This structured format made it easier to compare key concepts, quickly identify the main benefits, and reinforce learning through real-world applications.

**Observation**

Compared with the previous responses, the use of Output Formatting did not introduce new information but substantially improved the presentation of the content. Organizing the answer into a comparison table reduced cognitive effort, facilitated topic-by-topic analysis, and created a format better suited for note-taking and quick revision.

#### 🛡️ Final Refinement

**Technique:** 
```text 
Audience Specification + Output Formatting + Guardrails + Source Grounding
```
**Prompt**
```text
Explain the advantages of investing in a CDB in a clear and beginner-friendly way. Organize the answer into the following sections: profitability, safety, liquidity, taxation, and ideal investor profile. Keep the explanation concise, avoid unnecessary technical jargon, and use only the information available in the provided sources.
```

**Response Summary**

The final prompt produced the most structured and beginner-friendly response of the experiment. The information was organized into clearly defined sections—profitability, safety, liquidity, taxation, and ideal investor profile—making the content easier to navigate and understand. By combining multiple prompt engineering techniques, the response remained concise, accurate, and fully grounded in the provided sources while avoiding unnecessary technical complexity.

**Observation**

This version demonstrated the value of combining prompt engineering techniques rather than relying on a single approach. Defining the target audience simplified the language, specifying the output structure improved readability, guardrails controlled verbosity, and grounding the response in the uploaded sources increased reliability. The resulting answer required minimal post-editing and was the most suitable for inclusion in the final study guide.

#### Experiment 3 – Traditional vs. Digital Banks

### 📌 Initial Prompt

**Technique:**  
```text
Baseline Prompt
```
**Prompt**
```text
Is there any difference in investing depending on whether the bank is physical or digital?
```

**Response Summary**

The initial response compared investing through traditional and digital banks by discussing differences in yield, minimum investment requirements, customer support, and user experience. It also highlighted similarities, such as FGC protection, taxation rules, and the availability of digital investment platforms across both banking models.

**Observation**

The response provided a comprehensive overview of the topic, but the information was presented as a continuous explanation with limited structure. Although the main differences were identified, the content was more descriptive than analytical, making it less suitable for quick comparison and decision-making.

### 🔄 Prompt Refinement

**Technique:** 
```text
Role Prompting + Output Formatting
```
**Prompt**
```text
Act as a personal finance expert. Compare the differences between investing through a traditional brick-and-mortar bank versus a digital bank. Analyze key aspects such as fees, investment product variety, financial safety (like deposit insurance), and customer service support. Provide the final response in a structured comparison table followed by a brief summary of recommendations for a beginner investor.
```

**Response Summary**

Assuming the role of a personal finance expert, NotebookLM produced a structured comparison between traditional and digital banks. The response was organized into a comparison table covering fees, product variety, financial safety, customer support, minimum investment, and expected yields. It concluded with practical recommendations tailored to beginner investors, including guidance on deposit insurance (FGC), minimum investment strategies, liquidity, and evaluating institutional credit ratings.

**Observation**

Compared with the baseline response, this version shifted from a descriptive explanation to a decision-oriented analysis. Role Prompting encouraged a more professional and advisory tone, while Output Formatting transformed scattered information into a comparison table that made similarities and differences immediately visible. The addition of actionable recommendations further increased the practical value of the response for someone beginning to invest.

### 🛡️ Final Refinement

**Technique:**
```text
Role Prompting + Task Decomposition + Output Formatting + Guardrails
```
**Prompt**
```text
Act as a senior financial advisor and wealth management expert. Your task is to provide a rigorous, objective comparison between investing through traditional brick-and-mortar banks versus digital banks, specifically tailored for an individual investor with a moderate risk profile. Core Dimensions to Analyze: Yield & Costs: Contrast management fees, brokerage fees, and the yield rates typically offered on fixed-income products (e.g., CDs/CDBs).Product Ecosystem: Compare the breadth of access to third-party funds, equities, and international markets.Risk & Capital Security: Evaluate institutional risk, liquidity risks, and how deposit insurance protections apply to both models.Relationship & Advisory: Contrast automated/AI-driven financial advice with dedicated human managers, focusing on high-stakes financial decision-making.Hidden Friction: Detail operational bottlenecks, such as daily withdrawal limits, account maintenance hidden fees, and app downtime risks.Output Formatting Rules:Start directly with a Markdown comparison table contrasting the 5 dimensions.Use a "Pros & Cons" bulleted list for each banking model.End with a 3-step actionable decision framework helping the user choose where to allocate their capital based on their monthly investment volume.Avoid generic financial advice or standard definitions of what a bank is. Proceed directly to the strategic analysis.
```

**Response Summary**

The final prompt generated the most comprehensive response of the experiment. Instead of providing only a comparison between traditional and digital banks, NotebookLM organized the analysis into multiple strategic dimensions, including investment costs, product ecosystem, capital security, advisory services, and operational limitations. It also presented a balanced list of advantages and disadvantages for each banking model and concluded with a three-step decision framework based on the investor's monthly investment volume, offering practical guidance tailored to different investment scenarios.

**Observation**

Combining multiple prompt engineering techniques significantly improved both the depth and the practical value of the response. Role Prompting encouraged a more professional and strategic perspective, Task Decomposition ensured that each decision factor was analyzed independently, Output Formatting produced a highly organized comparison, and Guardrails kept the response focused on the requested analysis. The resulting output evolved from a simple explanation into a structured decision-support guide requiring virtually no post-editing.

### 🩹 Prompt Engineering Scars

The prompt engineering process was iterative rather than linear. Throughout the experiments, several challenges required adjustments to the prompts and influenced the final approach.

#### 1. Similar Responses

One of the first challenges was obtaining noticeably different results from small changes to the prompt. In some cases, simply rephrasing a question produced responses with very similar content. This showed that meaningful improvements often require changes to the instructions, structure, or constraints rather than wording alone.

#### 2. Controlling the Level of Detail

More detailed prompts did not necessarily produce better study material. Some responses contained useful information but were too extensive for quick review. Introducing constraints such as concise explanations, beginner-friendly language, and predefined sections helped balance depth and readability.

#### 3. Structuring Information for Learning

The initial responses were generally informative, but their format was not always optimized for studying. Techniques such as Output Formatting and structured instructions helped transform generic explanations into tables, categorized summaries, and decision frameworks.

#### 4. Controlling the Scope of the Analysis

As the prompts became more sophisticated, there was a risk of the response becoming broader than the original objective. Explicitly defining the dimensions to analyze and restricting the response to the provided sources helped maintain focus and relevance.

#### Key Learning

The main lesson from these challenges was that effective prompt engineering is an iterative process. Better results did not come from simply making prompts longer, but from defining the desired audience, structure, scope, and constraints according to the learning objective.


### 📖 Mini Study Guide

The final stage of the project was the creation of a concise and reusable study guide based on the knowledge developed throughout the NotebookLM experiments.

The guide consolidates the main concepts related to CDB investments, including how CDBs work, their advantages, types of remuneration, important factors to consider before investing, and differences between traditional and digital banks.

It also includes a glossary of key financial concepts and a collection of reusable prompts developed from the prompt engineering experiments.

👉 **[Access the CDB Mini Study Guide](./mini-guide/cdb-study-guide.md)**

### 🎯 Final Reflection

This project demonstrated how NotebookLM can be used not only as a source of information, but as a learning assistant capable of supporting research, source curation, critical thinking, and knowledge organization.

The iterative prompt engineering process showed that the quality of an AI-generated response depends not only on the information available to the model, but also on how the task, audience, structure, and constraints are defined.

This first project served as a practical introduction to AI-assisted learning and provided a foundation for exploring more advanced applications in future projects.
