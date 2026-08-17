# Technology Advisory Project

## Your challenge

This is a half-day **research project and group teaching challenge**. Your team will become the consultants and advisors on one important data technology used in modern banking. You will investigate the technology, decide what the rest of the cohort most needs to understand, and develop a **10-minute presentation** that explains it clearly in a banking context.

The three teams will cover different but connected areas: **Data Lakes vs. Data Warehouses**, **Distributed Compute & Streaming**, and **NoSQL**. After all teams have presented, you will run a group quiz using five questions prepared by each team.

By the end of your presentation, the audience should be able to explain:

- what the technology is and the problem it addresses;
- the most important concepts and terminology;
- where it might be useful in banking;
- its strengths, limitations and trade-offs; and
- how it relates to other technologies.

## Deliverable Assets:

**Quiz questions:** You must create **5 quiz questions** that test the most important things the audience should have learned from your presentation.

**Slide Deck:** You have a maximum of **8 slides**.

---

# Team 1 — Data Lakes vs. Data Warehouses

### Core concept

Help the audience understand the fundamental difference between **data lakes and data warehouses**, and why an organisation such as a bank might use one, the other, or both.

### Questions to explore

- What is a data lake? What is a data warehouse?
- Why did each approach emerge? What problems were they intended to solve?
- What kinds of data might a bank want to store?
- What is the significance of **schema-on-write** versus **schema-on-read**?
- What are the main trade-offs between a lake and a warehouse?
- When might a bank prefer one approach, and when might it use both?
- What challenges arise around data quality, governance, security and lineage?
- How has the distinction between lakes and warehouses evolved?
- What does the modern technology landscape look like?

### Five keywords everyone in the group should be able to define

1. **Data Lake**
2. **Data Warehouse**
3. **Schema-on-write**
4. **Schema-on-read**
5. **ETL vs. ELT**

### Banking angle

Start with a realistic banking situation. For example, imagine a bank dealing with transaction data, customer data, market data, mobile-app data and other information from many different systems.

What challenges does this create around **storing, organising and analysing data**?

Use the scenario to explore the technology rather than simply describing it.

### Case studies

Explore how a real company has used data lakes, data warehouses, or a specific provider's technology for a specific use case. Investigate how the technology was used and the outcome. This example does not need to be finance related.

### Players and terminology

Become familiar with some of the major names in the space, such as Snowflake, Databricks, Amazon Redshift, BigQuery, Microsoft Fabric/Azure.

The aim is to understand at a high level **what these technologies are and where they fit**.

---

# Team 2 — Distributed Compute & Streaming

### Core concept

Help the audience understand how **large-scale computation can be spread across multiple machines**, and how this idea relates to **processing continuously arriving data**.

### Questions to explore

- Why might a bank need to process data across many machines rather than on one machine?
- What actually happens when a computational task is distributed?
- What are the benefits and complications of distributing work?
- What is the difference between **batch processing** and **stream processing**?
- What makes a streaming system different from simply processing data quickly?
- What happens when data is arriving continuously?
- What concepts are important in a streaming architecture?
- What happens when one machine or component fails?
- What kinds of banking problems benefit particularly from distributed processing or streaming?
- How do technologies such as Kafka, Spark and Flink fit into the ecosystem?

### Five keywords everyone in the group should be able to define

1. **Distributed Computing**
2. **Parallelism**
3. **Batch Processing**
4. **Event Streaming**
5. **Partitioning**

### Banking angle

Consider a situation such as:

> A bank needs to monitor millions of transactions and identify potentially suspicious behaviour quickly.

What does this tell you about **scale, latency, processing and system architecture**?

Use the scenario as a route into the technology.

### Case studies

Explore how a real company has used distributed compute or streaming technologies (or a specific provider's offering) for a specific use case. Investigate how the technology was used and the outcome. This example does not need to be finance related.

### Players and terminology

Investigate technologies and companies such as Apache Kafka, Confluent, Apache Spark, Apache Flink and Databricks.

The important question is:

> **What job does each technology perform, and how do they fit together?**

---

# Team 3 — NoSQL

### Core concept

The audience is already familiar with the **high-level idea of NoSQL**. Your focus should therefore be on the **different structures and data models within NoSQL**, and why you would choose one over another.

Help the audience develop a practical mental model of the major NoSQL structures, particularly the differences between **document, key-value, column-family and graph databases**.

### Questions to explore

- What are the main NoSQL data models?
- How does each model represent information?
- What types of data or relationships are each model particularly well suited to?
- How does the underlying structure affect the kinds of queries or operations that are easy to perform?
- When would a **document database** be a better fit than a **graph database**?
- When would a **key-value store** make more sense?
- What does a graph database allow you to express that is difficult or unnatural in other models?
- How are graph databases being used alongside Large Language Models (LLMs), such as in tools like Microsoft Copilot?
- What are the key trade-offs between the different models?
- Could the same banking problem be represented in several NoSQL models? What changes when you do so?
- How do products such as MongoDB, DynamoDB, Cassandra and Neo4j relate to these different structures?

### Five keywords everyone in the group should be able to define

1. **Document Database**
2. **Key-Value Store**
3. **Column-Family Database**
4. **Graph Database**
5. **Data Model**

### Banking angle

Use one or two banking scenarios to demonstrate why the choice of data model matters.

For example:

**Customer profile / account information**

How might this look in a document database? What makes a document structure useful for this type of information?

**Customer, account, device and transaction relationships**

How might this look in a graph database? What becomes easier when relationships are represented explicitly?

**AI and Chatbots**

How might a bank use a graph database to provide accurate knowledge to an internal LLM or chatbot (e.g., grounding Microsoft Copilot with complex institutional relationships)?

The aim is not to produce four separate product descriptions. Instead, show how **the shape of the problem influences the choice of structure**.

### Case studies

Explore how a real company has used a NoSQL technology (or a specific provider's offering) for a specific use case. Investigate how the technology was used and the outcome. This example does not need to be finance related.

### Diagram ideas

This topic is particularly suited to visual explanation.

Consider showing the **same information represented in different models**, for example:

> **Document** → customer as a JSON-like record  
> **Key-value** → customer ID → customer information  
> **Column-family** → data organised for particular large-scale access patterns  
> **Graph** → customer → account → device → merchant

A particularly useful visual could ask:

> **What does this model make easy to see or retrieve?**

You could also show the same banking question being answered using two different models and explain why one structure is more natural than the other.

### Players and terminology

Become familiar with examples such as:

- **MongoDB** — document
- **DynamoDB** — key-value / document
- **Cassandra** — wide-column
- **Neo4j** — graph

The important question is not simply **What products exist?**, but:

> **What data model does each product use, and what kinds of problems does that make it well suited to?**

### The key takeaway

By the end of your presentation, the audience should be able to look at a problem and start asking:

> **What shape does the data have, what relationships matter, and which NoSQL model best fits the way we need to use it?**

---

# Your presentation

Plan a **10-minute presentation**, with a maximum of **8 slides**.

Think of yourselves as advisors explaining a technology to people who may not know much about it.

A strong presentation might explore questions such as:

- What problem are we trying to solve?
- Why is it difficult?
- What does this technology change?
- How does it work at a high level?
- What are the trade-offs?
- What alternatives exist?
- Who are the important players?
- Where might a bank actually use this?
- What should someone consider before choosing it?

You do not need to answer these questions in this order, and you do not need to cover every question. Use them to decide what is most important for your audience to understand.

## Visuals

Consider diagrams that help explain the technology.

Useful visuals might show:

- how information flows through a system;
- how components interact;
- how different approaches compare;
- how data is represented;
- or what happens before and after introducing the technology.

The key question is:

> **Does this visual make the concept easier to understand?**

---

# Your five-question quiz

Your group must create **5 questions** for the other groups.

The questions should test the **key learning from your presentation**.

The questions should be answerable by someone who has paid attention to your presentation, without needing to do additional research.

---

# Optional stretch goal — live demo

Once your presentation is ready, you may consider preparing a short live demo.

Research what might be achievable within the time available and decide whether a demo would genuinely strengthen your presentation.

The demo should remain a **secondary goal**. Do not let it distract from delivering a clear presentation.

---
