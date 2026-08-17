# Technology Advisory Project

## Your challenge

This is a half-day **research project and group teaching challenge**. Your team will become the consultants and advisors on one important data technology used in modern banking. You will investigate the technology, decide what the rest of the cohort most needs to understand, and develop a **10-minute presentation** that explains it clearly in a banking context.

The three teams will cover different but connected areas: **Data Lakes vs. Data Warehouses**, **Distributed Computing**, and **NoSQL**. After all teams have presented, you will run a group quiz using five questions prepared by each team.

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


# Your presentation

Plan a **10-minute presentation**, with a maximum of **8 slides**.

Think of yourselves as advisors explaining a technology to people who may not know much about it.

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

# Team 2 — Distributed Computing

### Core concept

Help the audience understand how **a computational problem can be divided across multiple machines so that they can work together to process larger workloads, improve performance and provide resilience**.

### Questions to explore

- Why might an organisation need to use multiple machines rather than one powerful machine?
- What is **partitioning**, and why is it important?
- What are the benefits of distributing computation?
- What new problems are created when multiple machines need to work together?
- What happens when one machine or component fails?
- How do distributed systems deal with failures and incomplete work?
- What kinds of problems are particularly well suited to distributed computing?
- What is the relationship between cloud computing and distributed computing?
- How do technologies such as **Apache Spark** implement distributed computation?

### Five keywords everyone in the group should be able to define

1. **Distributed Computing**
2. **Parallelism**
3. **Partitioning**
4. **Fault Tolerance**
5. **Scalability**

### Banking angle

Consider a situation such as:

> A bank needs to analyse billions of transactions to identify patterns, calculate risk and detect potentially suspicious behaviour.

Use the scenario to explore:

- Why one machine might not be sufficient
- How the workload could be divided across many machines
- How the machines can work on different parts of the problem simultaneously
- What happens if one machine fails
- How the system can scale as the workload grows
- Whether distributing the computation actually makes the problem easier or introduces new complications

The aim is to use the banking scenario to explain **why distributed computing exists**, rather than simply describing the technology.

### Case study

Explore how a real company has used **distributed computing** to solve a specific large-scale problem.

The example does not need to be finance related.

### Technology and terminology

Investigate **Apache Spark** as an example of a distributed computing framework.

The important question is:

> **How does Spark enable computation to be distributed across multiple machines?**

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
