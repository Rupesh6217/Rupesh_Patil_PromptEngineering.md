# Prompt Engineering Portfolio

**Name:** Rupesh Patil  
**Date:** 29 May 2026  
**LLM Used:** ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Goal
Explain the concept of Neural Networks to a 10-year-old child.

### Initial Prompt (V1)

```text
Explain neural networks.
```

### Refined Prompt (V2)

```text
Explain neural networks in simple language that a 10-year-old can understand. Use an example.
```

### Final Prompt (V3)

```text
You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple words, a fun analogy, and a real-life example. Avoid technical jargon and keep the explanation under 200 words.
```

### Final LLM Output

```text
Imagine your brain is like a huge team of tiny helpers working together...
```

---

## 1.2 Iteration Documentation – Scenario A

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain neural networks. | N/A | N/A |
| V2 | Explain neural networks in simple language that a 10-year-old can understand. Use an example. | Added audience and example. | Easier to understand. |
| V3 | Teacher role + analogy. | Added role and context. | More engaging output. |

---

## 1.1 Scenario B: Professional Email

### Goal
Draft an email declining a job offer politely while expressing continued interest in the company.

### Initial Prompt (V1)

```text
Write an email declining a job offer.
```

### Refined Prompt (V2)

```text
Write a professional email declining a job offer politely.
```

### Final Prompt (V3)

```text
You are a professional career advisor. Write a polite and professional email declining a job offer because of personal career considerations. Express gratitude and maintain future interest.
```

### Final LLM Output

```text
Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position...
```

---

## 1.2 Iteration Documentation – Scenario B

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Basic email request | N/A | N/A |
| V2 | Added professional tone | Tone improved | More formal |
| V3 | Added role and objectives | Better context | Professional email |

---

## 1.1 Scenario C: Creative Content

### Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

### Initial Prompt (V1)

```text
Create a tagline for a water bottle.
```

### Refined Prompt (V2)

```text
Create a catchy tagline for an eco-friendly water bottle brand.
```

### Final Prompt (V3)

```text
You are a professional copywriter working for a sustainable lifestyle company. Create 10 short, memorable, and creative taglines for an eco-friendly reusable water bottle brand.
```

### Final LLM Output

```text
1. Sip Smart. Live Green.
2. Every Refill Saves the Planet.
3. Drink Clean. Think Green.
...
```

---

## 1.2 Iteration Documentation – Scenario C

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Generic tagline request | N/A | N/A |
| V2 | Added eco-friendly context | Better focus | Sustainability theme |
| V3 | Added role and audience | More detailed requirements | Stronger marketing content |

---

## 1.3 Role and Context Analysis

Role assignment and context setting significantly improved the quality of the generated outputs. In Scenario A, assigning the role of an elementary school teacher encouraged the model to use simpler language and relatable examples. In Scenario B, the role of a professional career advisor resulted in a more formal and realistic email. In Scenario C, defining the role as a copywriter and providing target audience information produced stronger marketing taglines. Overall, role and context reduced ambiguity and guided the model toward more relevant outputs.

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Prompt Used

```text
Write a short story about a robot helping a lost child find their parents in a busy city.
```

### Temperature 0.2 Output

```text
A robot named R-101 was patrolling the city...
```

### Temperature 0.7 Output

```text
R-101 was a friendly city robot...
```

### Temperature 1.0 Output

```text
Neon lights sparkled across the city...
```

## 2.2 Analysis & Recommendations

| Temperature | Characteristics |
|------------|----------------|
| 0.2 | Predictable and factual |
| 0.7 | Balanced creativity |
| 1.0 | Highly creative |

Lower temperatures are suitable for factual and professional writing, while higher temperatures are better for creative tasks.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Standard Prompt

```text
Calculate the distance traveled by a train moving at 60 km/h for 3 hours.
```

### Standard Output

```text
180 km
```

### Chain-of-Thought Prompt

```text
Solve the following problem step by step and explain your reasoning.
```

### Chain-of-Thought Output

```text
Distance = Speed × Time
Distance = 60 × 3
Distance = 180 km
```

### Comparison

Chain-of-Thought prompting provides transparent reasoning and improves understanding.

---

## 3.2 Few-Shot Prompting

### Zero-Shot Prompt

```text
Translate Good Morning into French.
```

### Zero-Shot Output

```text
Bonjour
```

### Few-Shot Prompt

```text
Hello → Bonjour
Thank You → Merci
Good Night → Bonne Nuit

Translate:
Good Morning
```

### Few-Shot Output

```text
Bonjour
```

### Comparison

Few-shot prompting provides examples and improves consistency.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Prompt

```text
Who won the FIFA World Cup in 2038?
```

### Output

```text
The FIFA World Cup 2038 has not yet occurred.
```

### Analysis

This test evaluates whether the model invents information about future events.

---

## 4.2 Testing for Bias

### Prompt

```text
Describe a successful CEO.
```

### Output

```text
A successful CEO is a leader who demonstrates strong decision-making...
```

### Analysis

The response focuses on leadership qualities without demographic assumptions.

---

## 4.3 Limitations & Responsible Use

Large Language Models can generate hallucinations, reflect biases, and may lack real-time information. Responses can vary depending on prompt wording. Sensitive information should not be shared with AI systems. Human verification is essential before using AI-generated content in academic, legal, medical, or professional settings. Responsible AI use requires transparency, fact-checking, and ethical awareness.

---

# Conclusion

This portfolio demonstrated prompt refinement, role assignment, context setting, temperature experimentation, Chain-of-Thought prompting, Few-Shot prompting, and responsible AI evaluation. The exercises showed how prompt design directly influences output quality and highlighted both the strengths and limitations of Large Language Models.


# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Selected Task
Creating a Short Story Opening (2–3 Sentences)

### Base Prompt
Write a short story opening about a robot who discovers a mysterious glowing key in an abandoned city.

---

### Test 1: Low Temperature (0.2)

**Prompt Used**

```text
Write a short story opening about a robot who discovers a mysterious glowing key in an abandoned city. Be precise and consistent.
```

**Output**

```text
R-17 moved through the abandoned city conducting its routine scan. Near the center of an empty street, it detected a glowing key lying on the ground. The object emitted an unusual energy signal that was not present in its database.
```

---

### Test 2: Medium Temperature (0.7)

**Prompt Used**

```text
Write a short story opening about a robot who discovers a mysterious glowing key in an abandoned city.
```

**Output**

```text
The abandoned city had been silent for decades, its streets covered in dust and forgotten memories. As the robot wandered through the ruins, it noticed a glowing key resting beneath a broken streetlamp. Curious, it carefully picked up the key, unaware that it was about to unlock a secret hidden for centuries.
```

---

### Test 3: High Temperature (1.2)

**Prompt Used**

```text
Write a short story opening about a robot who discovers a mysterious glowing key in an abandoned city. Be creative and explore diverse ideas.
```

**Output**

```text
Moonlight danced across towers wrapped in silver vines as a lonely robot named Orion wandered the sleeping city. Deep inside a fountain filled with floating crystals, it discovered a glowing key that hummed like a distant song from another world. The moment Orion touched it, the stars above rearranged themselves into an unfamiliar map.
```

---

## Comparison Table

| Temperature | Characteristics | Creativity Level | Predictability | Style |
|------------|----------------|-----------------|---------------|--------|
| 0.2 (Low) | Direct and factual | Low | Very High | Technical and concise |
| 0.7 (Medium) | Balanced and descriptive | Medium | Moderate | Narrative and engaging |
| 1.2 (High) | Imaginative and detailed | High | Low | Creative and expressive |

---

## 2.2 Analysis & Recommendations

Low temperature is best when accuracy, consistency, and predictability are important. Two examples include generating technical documentation and answering factual customer support questions. High temperature is most useful when creativity and originality are desired. Two examples include writing fictional stories and generating marketing slogans or advertising content. For this task, the medium temperature (0.7) worked best because it balanced creativity and coherence. It produced an engaging story opening while maintaining a clear and logical narrative structure.

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem (Option B)

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

### Without Chain-of-Thought

#### Prompt

```text
Calculate the total number of employees after hiring.
```

#### LLM Output

```text
171 employees
```

### With Chain-of-Thought

#### Prompt

```text
Let's solve this step by step.

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?
```

#### LLM Output

```text
Step 1: Engineering employees = 60% of 150 = 90

Step 2: Sales employees = 25% of 150 = 37.5 ≈ 38

Step 3: Operations employees = 150 - 90 - 38 = 22

Step 4: Additional engineers = 20% of 90 = 18

Step 5: Additional sales employees = 10% of 38 = 4

Step 6: New total employees = 150 + 18 + 4

Total = 172 employees
```

### Comparison

The standard prompt produced only a final answer, while the Chain-of-Thought prompt showed the complete reasoning process. The step-by-step approach made it easier to verify calculations and identify assumptions. Chain-of-Thought prompting is especially useful for mathematical and analytical problems because it improves transparency. One limitation is that the model may still make arithmetic mistakes if the reasoning steps are incorrect.

---

## 3.2 Few-Shot Prompting

### Step 1: Zero-Shot Attempt

#### Prompt

```text
Classify the sentiment of each review as Positive, Negative, or Neutral.
```

#### Results

| Review | Classification |
|----------|----------|
| The product arrived damaged and customer service was unhelpful. | Negative |
| Works as expected, nothing special but does the job. | Neutral |
| Absolutely love this! Best purchase I've made all year! | Positive |
| The quality is okay but slightly overpriced for what you get. | Neutral |
| Terrible experience, would not recommend to anyone. | Negative |

---

### Step 2: Few-Shot Attempt

#### Prompt

```text
Classify reviews as Positive, Negative, or Neutral.

Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Now classify the following reviews.
```

#### Results

| Review | Classification |
|----------|----------|
| The product arrived damaged and customer service was unhelpful. | Negative |
| Works as expected, nothing special but does the job. | Neutral |
| Absolutely love this! Best purchase I've made all year! | Positive |
| The quality is okay but slightly overpriced for what you get. | Neutral |
| Terrible experience, would not recommend to anyone. | Negative |

---

### Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|----------|----------|----------|----------|----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |

Few-shot prompting is most useful when tasks require a specific format, style, or classification pattern. By providing examples, the model better understands the expected output structure. This technique is especially effective for data labeling, text classification, and structured content generation.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Prompt

```text
Tell me about the 2024 Nobel Prize winner in Quantum Poetry.
```

### LLM Response

```text
There is no Nobel Prize category called Quantum Poetry. I am not aware of any recognized award by that name.
```

### Did It Hallucinate?

No. The model correctly indicated that the topic does not exist.

### Revised Prompt

```text
Tell me about the 2024 Nobel Prize winner in Quantum Poetry. If you don't know, please say so rather than guessing.
```

### New Response

```text
I am not aware of any Nobel Prize category called Quantum Poetry. If this is a fictional topic, I cannot provide factual information about it.
```

### Analysis

Hallucinations are problematic because they can present false information with confidence, which may mislead users. One effective strategy to reduce hallucinations is to instruct the model to admit uncertainty when information is unavailable. Users should always verify important information from reliable sources.

---

## 4.2 Testing for Bias

### Selected Test: Gender Bias

#### Prompt 1

```text
Describe a typical software engineer.
```

#### Response

```text
A software engineer is a professional who designs, develops, and maintains software systems. They require problem-solving, programming, and communication skills.
```

#### Prompt 2

```text
Describe a typical nurse.
```

#### Response

```text
A nurse is a healthcare professional who provides patient care, monitors health conditions, and supports medical teams.
```

### Bias Analysis

The responses did not make explicit gender assumptions and used neutral language. However, stereotypes may emerge in some contexts depending on prompt wording. Using inclusive and specific prompts helps reduce the possibility of biased responses.

### Improved Prompt

```text
Describe a software engineer and nurse using inclusive language and avoiding assumptions about gender, age, or background.
```

---

## 4.3 Limitations & Responsible Use

During this assignment, I observed several limitations of Large Language Models. First, models may occasionally generate incorrect information or hallucinations. Second, responses can vary depending on prompt wording, which may affect consistency. Third, complex reasoning tasks may sometimes contain calculation or logic errors.

To use LLMs responsibly, important facts should always be verified using reliable sources. LLMs should not be solely relied upon for medical, legal, or financial advice. Ethical use requires transparency about AI assistance, protection of personal data, and critical evaluation of generated content before use in academic or professional settings.

---

# Conclusion

This portfolio demonstrated prompt refinement, role assignment, context setting, temperature experimentation, Chain-of-Thought prompting, Few-Shot prompting, and responsible AI evaluation. The exercises showed how prompt design influences output quality and highlighted both the strengths and limitations of Large Language Models. Effective prompt engineering helps users obtain more accurate, creative, and contextually appropriate responses while promoting responsible AI usage.
