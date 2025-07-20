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

---

# Notes on Deep Learning & Neural Networks

## Neural networks & deep learning

- The terms **deep learning** and **neural network** are often used interchangeably in AI.
- Neural networks are a fundamental tool in deep learning.
- There is hype and mystique around them, but at their core, they are systems that **learn to map inputs to outputs**.

---

## Example: T-shirt demand prediction

### Simple case (single neuron)

- Goal: Predict how many t-shirts you'll sell based on price.
- **Input**: Price of the t-shirt.
- **Output**: Estimated demand.
- Can be represented as a **straight line** showing that higher prices reduce demand.
- This setup = one **artificial neuron**, mapping price to demand.

### More complex case (small network)

- Additional factors:
  - Shipping cost.
  - Marketing budget.
  - Material quality.
- Intermediate concepts (hidden neurons):
  - **Affordability**: Based on price and shipping cost.
  - **Awareness**: Based on marketing.
  - **Perceived quality**: Based on price, marketing, and material.
- These intermediate factors are computed by **hidden neurons**.
- Final neuron combines them to estimate demand.
- In practice, modern networks have **thousands or millions of neurons**, much more complex than this example.

---

## Key idea: Neurons like Lego blocks

- Each neuron performs a simple computation.
- By stacking many neurons together, you can represent **very complex functions**.
- You do **not** manually program the intermediate steps — the network **learns them from data**.

---

## Training neural networks

- Provide:
  - **Inputs (A)**: E.g., price, shipping, marketing.
  - **Outputs (B)**: E.g., actual demand.
- The network automatically learns the best way to map A → B, including figuring out what intermediate neurons should compute.

---

## Example: Face recognition

### How a computer "sees" images

- Images = grid of pixel values.
  - Grayscale: One number per pixel.
  - Color: Three numbers per pixel (red, green, blue).
- Example: 1000 × 1000 color image = 3 million numbers.

### What the neural network does

- **Input**: Pixel brightness values.
- **Hidden layers**:
  - Early neurons detect **edges**.
  - Middle neurons detect **object parts** (eyes, noses, mouths).
  - Later neurons identify **whole faces**.
- **Output**: Person’s identity.

- You do **not** program how to find edges or faces — the network figures this out on its own.

---

**Key takeaways**

- Neural networks can learn **complex mappings** from inputs to outputs.
- Require **large datasets** for training.
- No need to explicitly define intermediate features.
- Applications include:
  - Demand prediction
  - Face recognition
  - Speech recognition
  - And many more.

---

# Building AI Projects

## Key steps of a **machine learning** project
1. **Collect data**
2. **Train model**
   - Iterate many times until performance is acceptable
3. **Deploy model**
   - Start getting real-world data back
   - Maintain and update the model over time

## Key steps of a **data science** project
1. **Collect data**
2. **Analyze data**
   - Iterate to uncover useful insights
3. **Suggest hypotheses or actions**
   - Deploy changes or business actions
   - Re-analyze new data periodically to measure impact

## Build vs. Buy
- **ML projects**: Can be built in-house or outsourced, depending on expertise and resources.
- **DS projects**: More commonly done in-house to leverage company-specific knowledge.
- Avoid building tools that are already widely available as industry standards ("don’t reinvent the wheel").

## Datasets

### Training Set
- A set of data points (e.g., images) with labels.
- Used to teach the model by providing both inputs (A) and desired outputs (B).

### Test Set
- A separate set of data points given to the trained model.
- Used to evaluate how well the model predicts outputs (B) from new inputs (A).

## Technical tools for AI teams

### Open-source machine learning frameworks
- **PyTorch**
- **TensorFlow**
- **Hugging Face**
- **PaddlePaddle**
- **Scikit-learn**
- **R**

### Deployment environments
- **Cloud**: Flexible, scalable, often easier to start with.
- **On-premises**: Greater control and security, but higher setup/maintenance cost.
- **Edge**: Running models on local devices for faster response and offline capabilities. Ex: self-driving car

---

# Building AI in Your Company

## Case Study: Smart Speaker

> Example: "Hey device, tell me a joke"

**Steps to process the command:**

1. **Trigger word / wake word detection**  
   - Audio → "Hey device"? (0/1)

2. **Speech recognition**  
   - Audio → "tell me a joke" → "joke"

3. **Intent recognition**

4. **Execute**  
   - Tell a joke

This sequence is called an **AI pipeline**.

---

> Example: "Hey device, set timer for 10 minutes"

**Steps to process the command:**

1. **Trigger word / wake word detection**  
   - Audio → "Hey device"? (0/1)

2. **Speech recognition**  
   - Audio → "set timer for 10 minutes"

3. **Intent recognition**  
   - "set timer for 10 minutes" → intent: timer

4. **Execution**  
   - a. Extract duration: "10 minutes"  
   - b. Start timer with the set duration

---

## Case Study: Self-Driving Car

**Steps for deciding how to drive:**

- **Input:** Image / radar / lidar
- The system needs to:
  - Detect other cars
  - Detect pedestrians
- Then, use this information in **motion planning**, which plans a path to avoid collisions.
- Finally, translate the planned path into **steering**, **acceleration**, and **braking** commands.

**Key steps:**

1. **Car detection** — using supervised learning
2. **Pedestrian detection**
3. **Motion planning** — outputs the path and speed for safe driving

---

## AI Transformation Playbook

### 1. Execute pilot projects to gain momentum
- Prioritize early success over maximum immediate value.
- Aim to show traction within 6–12 months.
- Can be executed in-house or outsourced.

### 2. Build an in-house AI team
- The AI function can sit under the CTO, CIO, CDO, or a new Chief AI Officer (CAIO).

### 3. Provide broad AI training
#### Executives and senior business leaders
- **What to learn**: AI strategy, resource allocation, understanding what AI can do for the enterprise.

#### Leaders of divisions working on AI projects
- **What to learn**: Set project direction (both technical and business diligence), resource allocation, monitor progress.

#### AI engineer trainees
- **What to learn**: Build and ship AI software, gather data, execute on specific AI projects.

### 4. Develop an AI strategy
- Leverage AI to create an industry-specific competitive advantage.
- Design a strategy aligned with the **Virtuous Cycle of AI**.
- Consider creating a data strategy:
  - Strategic data acquisition.
  - Unified data warehouse.
- Create network effects and platform advantages:
  - In industries with "winner-take-all" dynamics, AI can accelerate market leadership.

### 5. Develop internal and external communications
- Investor relations.
- Government relations.
- Customer and user education.
- Talent and recruitment.
- Internal communications.

---

# AI Application Areas

AI today is widely applied to:
- Image and video data
- Language data
- Speech data
- Structured and unstructured data

---

## Computer Vision

### Image Classification & Object Recognition
- Classifies images into categories (e.g., cat, flower, food).
- Used in many applications (e.g., product recognition, medical imaging).

### Face Recognition
- Identifies or verifies people based on facial images.
- Applications: unlocking phones, security systems.
- Important: must respect privacy.

### Object Detection
- Detects and locates objects within an image.
- Example: self-driving cars identifying pedestrians and vehicles.

### Image Segmentation
- Labels each pixel in an image (e.g., which pixels belong to a car or a pedestrian).
- Useful in medical imaging (e.g., segmenting organs).

### Video Tracking
- Tracks moving objects over time in videos.
- Examples: sports tracking, wildlife monitoring.

---

## Natural Language Processing (NLP)

### Text Classification
- Categorizes text (e.g., spam vs. non-spam, product categories).
- Example: sentiment analysis (e.g., star ratings from reviews).

### Information Retrieval
- Finds relevant documents based on queries.
- Example: web search, internal document search.

### Named Entity Recognition (NER)
- Identifies names of people, places, companies in text.

### Machine Translation
- Translates text from one language to another.

---

## Speech and Audio

### Speech Recognition (Speech-to-Text)
- Converts audio waveforms into text.
- Example: transcribing spoken words.

### Trigger/Wake Word Detection
- Detects activation words (e.g., "Hey Google").

### Speaker Identification
- Identifies a person by their voice.

### Speech Synthesis (Text-to-Speech, TTS)
- Converts text into spoken audio.
- Modern systems sound increasingly natural.

---

## Generative AI

### Text Generation
- Generates new text (e.g., writing, summarizing, editing, brainstorming).

### Image Generation
- Creates images from text prompts.
- Examples: Midjourney, Adobe Firefly.

### Audio Generation
- Generates music and sound effects from text prompts.
- Examples: Stable Audio, Meta’s Audiocraft.

---

## Robotics

### Perception
- Understands the environment using sensors (e.g., cameras, lidar).

### Motion Planning
- Plans paths and movements (e.g., turning a self-driving car).

### Control
- Executes actions by controlling hardware (e.g., steering, acceleration).

---

## Structured Data

- AI is also widely used on structured (tabular) data.
- While less publicized, it creates significant economic value.

---

## AI Learning Techniques

- **Supervised Learning**: Learn from labeled data (input-output pairs).
- **Unsupervised Learning**: Find patterns without explicit labels.
- **Reinforcement Learning**: Learn actions based on rewards.

---

## Conclusion

- AI applications are broad and impactful across many domains.
- Consider how these techniques might help in your own projects.

---

# AI and Machine Learning Techniques

## Supervised vs Unsupervised Learning

### Supervised Learning
- Maps input **A** to output **B**.
- Requires **labeled data**.
- Example: Identifying objects like coffee mugs using thousands of labeled images.

### Unsupervised Learning
- No explicit labels or outputs given.
- Finds patterns and structures in data automatically.

#### Example: Clustering
- Use case: A grocery store selling potato chips.
  - **Cluster 1**: Customers buying lots of cheap chips (e.g., college students).
  - **Cluster 2**: Customers buying fewer, more expensive chips (e.g., professionals).
- Helps with **market segmentation** and targeted marketing.
- Example in AI: The "Google cat" project, where an algorithm identified cats from YouTube videos without being told explicitly.

#### Advantages
- Requires **less labeled data**.
- Potential for more **human-like learning** in the future.
- Currently used in some applications (e.g., web search), but **economic value today is smaller** than supervised learning.

---

## Transfer Learning

### Concept
- Transfers knowledge from one task (**Task A**) to another related task (**Task B**).
- Useful when **Task B** has limited data.

#### Example
- Train a model to detect cars using a large dataset.
- Reuse knowledge to detect golf carts with fewer images.

### Benefits
- Reduces data and time needed for new tasks.
- Widely used in computer vision and other AI fields.

---

## Reinforcement Learning

### Concept
- Learns by **trial and error**, guided by rewards and penalties (similar to training a dog).
- Uses a **reward signal**:
  - Positive reward → "Good job"
  - Negative reward → "Bad job"
- Goal: Maximize accumulated rewards over time.

#### Example
- Stanford autonomous helicopter project.
  - AI flies in a simulator.
  - Gets rewarded for stable or impressive maneuvers.
  - Learns to fly even upside down through reward signals.
- Popular in robotics and games (e.g., AlphaGo, video games).

#### Challenges
- Requires **huge amounts of data** (can simulate or self-play in games).
- Harder to apply where data is scarce or simulations are difficult.

---

## GANs (Generative Adversarial Networks)

### Concept
- Introduced by Ian Goodfellow.
- Can **generate realistic new data** (e.g., images) from scratch.

#### Example
- NVIDIA project creating realistic images of non-existent celebrities.
- Applications in:
  - Entertainment
  - Gaming
  - Graphics
  - Content generation

---

## Knowledge Graphs

### Concept
- Databases that store structured information about entities (e.g., people, places, hotels).
- Enable quick retrieval of key facts and connections.

#### Example
- Google search panels showing detailed info about people like Leonardo da Vinci or Ada Lovelace.
- Used to power search engines, maps, and recommendation systems.

### Importance
- Creates significant economic value.
- Surprisingly understudied in academia despite widespread real-world impact.

---

## Summary

- Explored **unsupervised learning**, **transfer learning**, **reinforcement learning**, **GANs**, and **knowledge graphs**.
- These techniques enable new capabilities beyond supervised learning.
- Understanding them can help you have more fruitful discussions with AI engineers and explore new project ideas.

---

# AI and Machine Learning Techniques

## 1. Supervised Learning
- **Definition**: Learning an A to B mapping; requires labeled data.
- **Economic Value**: Currently the most valuable and widely used AI technique.
- **Example**: Training an AI to recognize coffee mugs using thousands of labeled images.

---

## 2. Unsupervised Learning
- **Definition**: Learning without labeled output (no “B” in A→B).
- **Goal**: Find patterns, structures, or groupings in data.

### Example: Clustering in a Grocery Store
- Data: Number of potato chip packets bought and average price per packet.
- Discovered Clusters:
  - College students: Buy many cheap packets.
  - Working professionals: Buy fewer, more expensive packets.
- **Use Case**: Market segmentation and targeted marketing.

### The Google Cat Project
- AI watched YouTube videos with no labels.
- **Result**: Learned the concept of a "cat" entirely on its own.
- **Significance**: Shows AI can extract meaningful concepts from raw data.

### Challenges with Supervised Learning
- Needs massive labeled datasets.
- Humans don’t need that many examples to learn (e.g. no child sees 10,000 coffee mugs).

### Promise of Unsupervised Learning
- **Potential**: Learn like humans or animals with less labeled data.
- **Current Use**: Helps improve NLP and web search, though still less economically impactful than supervised learning.

---

## 3. Transfer Learning
- **Definition**: Applying knowledge from one task (A) to another related task (B).

### Example
- Task A: Car detection using 100,000 images.
- Task B: Golf cart detection with only a few images.
- **Advantage**: Leverages shared features (e.g. wheels, vehicle shapes) to perform well on new tasks with less data.
- **Applications**: Widely used in computer vision systems.

---

## 4. Reinforcement Learning (RL)
- **Definition**: Learning by receiving rewards (positive or negative) based on actions.

### Example: Stanford Autonomous Helicopter
- Equipped with GPS, accelerometers, compass.
- Trained using trial-and-error in a simulator.
- Rewarded for flying well, penalized for crashing.
- **Result**: Learned to fly—even upside down!

### Analogy: Training a Dog
- Good behavior → "Good dog!" (positive reward)
- Bad behavior → "Bad dog!" (negative reward)

### Key Concepts
- Uses **reward signals** to guide learning.
- Learns to **maximize cumulative rewards**.

### Applications
- Robotics (e.g. helicopters)
- Games (e.g. Go, Chess, video games like AlphaGo)
- Simulated environments allow for infinite training data.

### Limitations
- Requires a **large amount of data**.
- Less economically impactful today than supervised learning, but has great research potential.

---

## 5. Generative Adversarial Networks (GANs)
- **Creator**: Ian Goodfellow (former student of the speaker).
- **Function**: Generate realistic new images from scratch.

### Example: NVIDIA GANs
- Trained on celebrity images.
- Created images of entirely fake but realistic people.

### Applications
- Entertainment, media, computer graphics, content generation.

---

## 6. Knowledge Graphs
- **Definition**: Databases of entities (people, places, etc.) and their attributes.

### Examples
- Google Search panels for people like **Leonardo da Vinci** or **Ada Lovelace**.
- Graphs for:
  - Hotels
  - Celebrities
  - Airports
  - Attractions

### Usage
- Enables fast information lookup and contextual search.

### Impact
- High **economic value**.
- Surprisingly **understudied** in academia.

---

## Summary
You’ve learned about:
- **Unsupervised Learning**
- **Transfer Learning**
- **Reinforcement Learning**
- **GANs**
- **Knowledge Graphs**

These techniques each offer unique strengths and applications in the field of AI. While supervised learning currently dominates in terms of economic impact, the others—especially unsupervised and reinforcement learning—may shape the future of AI with more human-like learning methods.

---

## AI and Society

### Bias in AI

- AI reflects societal bias in data and decisions.
- **Types of bias:**
  - **Data bias** (e.g., past discrimination reflected in datasets).
  - **Labeling bias** (human judgments).
  - **Deployment bias** (used in inappropriate contexts).

**Example:** Loan approval AI trained on biased credit data may deny loans unfairly.

---

### Fairness in AI

- No universal definition; fairness depends on context.

**Common fairness types:**
- **Demographic parity**: Equal outcomes across groups.
- **Equalized odds**: Equal error rates across groups.
- **Individual fairness**: Similar people get similar predictions.

**Note:** Increasing fairness often decreases performance (trade-off).

---

### Privacy in AI

- AI relies on user data → raises privacy concerns.
- **Risks:**
  - Data leaks.
  - Inference of sensitive information.
  - Re-identification of anonymized individuals.

**Solutions:**
- Data minimization.
- Anonymization and aggregation.
- Use of techniques like **differential privacy** or **federated learning**.

---

### Ethics and Responsibility

- AI decisions can have major consequences (e.g., in healthcare, law).
- Who is accountable when AI fails?
  - The developers? The company? The data providers?

**Key questions:**
- Was user consent obtained?
- Can users understand the AI’s reasoning?
- Are humans still in control?

---

### Social Impact of AI

**Positive Impacts:**
- Better healthcare diagnosis.
- Personalized education.
- Increased accessibility (e.g., speech-to-text).
- Economic productivity.

**Negative Impacts:**
- Job displacement.
- Widening inequality.
- Misinformation (deepfakes, fake news).
- Surveillance misuse.

**Role of Policy:**
- Need regulation and governance.
- Ethical AI boards and audits.
- Inclusion of diverse voices in AI development.
