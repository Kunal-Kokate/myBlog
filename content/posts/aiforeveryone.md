---
date: '2025-07-08T11:11:11-05:00'
draft: false
toc: true
title: 'AI For Everyone Course Notes'
tags: ["AI", "", ""]
categories: ["AI", "Course Notes"]
---

# AI

Artificial Intelligence (AI) refers to machines or software that can perform tasks typically requiring human intelligence. It can be categorized into different types:

## ANI (Artificial Narrow Intelligence)

Artificial Narrow Intelligence (ANI) is designed to perform a specific task or a narrow range of tasks. These systems are highly specialized and cannot perform functions outside of their programmed capabilities.

**Examples:**
- Smart speakers (like Amazon Alexa or Google Home)
- Self-driving cars
- Web search engines
- AI used in farming (e.g., crop monitoring, automated harvesting)
- AI in factories (e.g., robotic arms, quality control systems)

## Generative AI (Generative Artificial Intelligence)

Generative AI refers to AI systems that can create new content such as text, images, audio, or code. These models learn patterns from large amounts of data and use that to generate original outputs.

**Examples:**
- ChatGPT (for generating text or answering questions)
- Bard (Google’s conversational AI)
- Midjourney (for creating images)
- DALL·E (for generating images from text descriptions)

## AGI (Artificial General Intelligence)

Artificial General Intelligence (AGI) describes a hypothetical form of AI that would be capable of understanding, learning, and performing any intellectual task that a human can do. AGI does not exist yet but is a major goal in AI research.

**Key point:**
- AGI would have the ability to reason, plan, solve problems, think abstractly, and learn across a wide range of tasks, just like humans.


# Machine Learning

## Supervised Learning

Supervised learning is a type of machine learning where the model learns to map an input (A) to an output (B). You train the model on a dataset that includes both inputs and their corresponding correct outputs.

**Concept:**  
A --> B    
Input --> Output  


### Examples

| **Input (A)**       | **Output (B)**            | **Application**          |
|---------------------|---------------------------|--------------------------|
| email               | spam (0/1)               | spam filtering          |
| audio               | text transcripts         | speech recognition      |
| English             | Spanish                   | machine translation     |
| ad, user info       | click (0/1)             | online advertising     |
| image, radar info   | position of other cars   | self-driving cars      |
| image of phone      | defect (0/1)            | visual inspection     |
| sequence of words   | next word               | chatbot                |

**Key points:**
- The "0/1" indicates a binary decision (e.g., spam or not spam, defect or no defect).
- The model learns from labeled examples (datasets where the correct answer is provided) to predict outputs on new, unseen data.


# How large language models (LLMs) work
- LLMs are built by using supervised learning (A->B) to repeatedly predict the next word

    My favorite drink is lychee bubble tea.
| **Input (A)**       | **Output (B)**            |
|---------------------|---------------------------|
| My favorite drink               | is               |
| My favorite drink is               | lychee         | 
| My favorite drink is lychee             | bubble                   | 
| My favorite drink is lychee bubble       | tea             | 

- When we train a very large AI system on a lot of data (hundreds of billions of words) we get a Large Language Model like ChatGPT

# Acquiring Data

There are different ways to collect data for AI projects:

## Manual Labeling

- Collect a set of images (or other data).
- Have humans manually go through each example and label it (e.g., "cat" vs "dog" or "defect" vs "no defect").

## Observing Behaviors

- Gather data by observing how people behave or interact with a system.
- Useful for capturing natural patterns and real-world scenarios.

## Downloading from Websites or Partnerships

- Obtain data by scraping websites (when permitted).
- Partner with other organizations or companies to access relevant datasets.

---

# Use and Misuse of Data

## Common Misunderstandings

- You can’t just throw a pile of data at an AI team and expect it to automatically be useful or valuable.
- Data quality and relevance are crucial.

## Data is Messy

- **"Garbage in, garbage out":** Poor-quality data will lead to poor AI performance.
- Common data issues include:
  - Errors and noise
  - Missing or incomplete values
  - Incorrect labels

## Multiple Types of Data

- **Unstructured data:** Images, audio, text (requires more processing to extract meaning).
- **Structured data:** Data stored in tables (e.g., spreadsheets or databases), with clearly defined fields.

---

**Key Takeaway:**  
Good data is the foundation of effective AI. Without clean, relevant, and properly labeled data, even the best algorithms will fail.



# Terminology of AI

## Machine Learning vs. Data Science

Imagine you have a housing dataset with:
- Size of house (sq ft)
- Number of bedrooms
- Number of bathrooms
- Whether it is newly renovated
- Price (in $1,000s)

### Machine Learning

If you want to build a mobile app to help people estimate house prices, you would use:
- **Inputs (A):** Size, number of bedrooms, number of bathrooms, renovated status
- **Output (B):** Price

A machine learning system learns the mapping from A to B (input to output).

**Definition:**  
> "Field of study that gives computers the ability to learn without being explicitly programmed." — Arthur Samuel (1959)

- The output is usually a piece of software that, given new inputs, can predict outputs automatically.
- **Example:** A pricing model for homes.

---

### Data Science

Data science focuses on analyzing data to extract insights and knowledge.

**Example conclusions:**
- "Homes with 3 bedrooms are more expensive than those with 2 bedrooms of similar size."
- "Newly renovated homes sell at a 15% premium."

- The output is often a report, slide deck, or presentation summarizing these insights.
- **Example:** A presentation showing price trends in different neighborhoods.

---

## Deep Learning

- A type of machine learning that uses **artificial neural networks** to learn complex patterns from data.
- Takes input(s) A and predicts output B.
- Very effective for tasks where traditional methods struggle, such as image recognition, speech recognition, and natural language understanding.

---

## AI Has Many Tools

AI is a broad field that includes many techniques and subfields, such as:
- **Machine learning** and **data science**
- **Deep learning** / neural networks
- **Generative AI** (e.g., models that create text or images)
- **Unsupervised learning** (finding patterns without labeled outputs)
- **Reinforcement learning** (learning through trial and error to maximize rewards)
- **Graphical models**, **planning**, **knowledge graphs**, and more

---

**Key Takeaway:**  
Machine learning builds systems that map input to output (A → B). Data science focuses on analyzing data to generate insights. Deep learning is a powerful modern approach to machine learning, using neural networks.


# What Makes an AI Company?

## A Lesson from the Rise of the Internet

### Internet Era

- If you take your favorite shopping mall and simply create a website to sell things, that does **not** make it an "Internet company."
- An Internet company is one that truly leverages what the Internet enables:
  - A/B testing at scale
  - Short iteration cycles and rapid updates
  - Decision-making pushed down to engineers and specialized teams rather than centralized executives

---

## AI Era

- Similarly, just adding a few deep learning models to your existing business does **not** make it an AI company.
- A true AI company focuses on:
  - **Strategic data acquisition** — intentionally collecting valuable data that gives a competitive advantage
  - **Unified data warehouse** — integrating data sources into a single, well-organized system
  - **Pervasive automation** — using AI to automate processes across the organization
  - **New roles and division of labor** — creating roles like machine learning engineers and rethinking team structures to support AI efforts

---

## AI Transformation

For traditional companies that want to effectively use AI, these are common steps:

1. **Execute pilot projects** to build early success and momentum.
2. **Build an in-house AI team** with dedicated experts and resources.
3. **Provide broad AI training** so more employees understand and can contribute to AI initiatives.
4. **Develop an AI strategy** to guide long-term decisions and investments.
5. **Develop internal and external communications** to align teams and share the company’s AI vision clearly.

---

# What AI Can and Cannot Do

## Developing Intuition for AI Projects

Before committing to an AI project, it’s important to evaluate whether it is actually feasible. This involves doing technical diligence:  
- Identify **input (A)** and **output (B)** clearly.  
- Consider whether this mapping can realistically be learned by AI.

---

## Overestimating AI

- Many CEOs and leaders tend to overestimate what AI can do today.
- The media and academic papers often focus only on success stories and positive results, creating a false impression that AI can do everything.
- In reality, AI has clear limitations.

---

## An Imperfect Rule of Thumb

A quick test:  
> If a human can do the task in **one second of thought**, it is more likely to be automatable with supervised learning.

**Examples of tasks that can likely be automated:**
- Determining the position of other cars (for self-driving cars)
- Detecting if a phone is scratched
- Transcribing speech into text

---

## Tasks AI Cannot Do Well Today

**Example:** Predicting stock prices  
- Task: Given past stock prices (input A), predict future prices (output B).
- Problem: Historical stock prices alone are not predictive enough.
- Attempts often fail because future prices are highly random and influenced by many unpredictable factors.

**Note:**  
Some traders try to use additional data (e.g., web traffic, foot traffic) to improve predictions, but these inputs are hard to get and don’t completely solve the problem.

---

## Additional Rules of Thumb for Feasibility

1. **Simple concepts are easier to learn.**  
   - If it takes you only a second or a few seconds to make a decision, it is likely a "simple concept."

2. **More data makes problems more feasible.**  
   - You need lots of examples of both input (A) and output (B).
   - Example: To detect phone scratches, you need thousands of labeled images (scratched vs. not scratched).

---

## Final Thoughts

- AI is like electricity: powerful and transformative, but not magic.
- You cannot expect AI to do everything.
- Building strong intuition helps you choose realistic and valuable projects for your team or company.
