# Few-Shot Prompting Exercises

Learn to guide AI responses by providing examples of the pattern you want it to follow.

---

## Understanding Few-Shot Prompting

Few-shot prompting means showing the AI 2-4 examples of what you want BEFORE asking it to do something similar. This teaches the AI the pattern, format, and style you expect.

**Basic Structure:**
```
Here are examples of what I want:

Example 1: [INPUT] → [OUTPUT]
Example 2: [INPUT] → [OUTPUT]
Example 3: [INPUT] → [OUTPUT]

Now please do the same for: [NEW INPUT]
```

---

## Exercise 1: Text Summarization - Teaching a Style

**Scenario:** You want the AI to summarize texts in a specific way for your class.

### 7th Grade Level: Summary Writing Style

**Goal:** Teach the AI to write summaries that are short, clear, and in your own words.

**Task:** Create 3 examples showing the pattern

**Example 1 - Original Text:**
```
The solar system contains eight planets orbiting the sun. Mercury is closest to
the sun and is very hot. Venus is next and has a thick atmosphere. Earth is our
home planet and is the only one with liquid water on its surface. Mars is the
red planet. Then come the gas giants: Jupiter, Saturn, Uranus, and Neptune.
Each planet is unique and fascinating.
```

**Example 1 - Good Summary (Model it for the AI):**
```
Our solar system has eight planets that orbit the sun. The inner planets
(Mercury, Venus, Earth, and Mars) are rocky, while the outer planets
(Jupiter, Saturn, Uranus, and Neptune) are gas giants. Earth is special
because it has liquid water.
```

**Example 2 - Original Text:**
```
Photosynthesis is the process plants use to make food. During the day, plants
take in sunlight, water, and carbon dioxide. Using the energy from sunlight,
the plant changes these ingredients into glucose (a type of sugar) and oxygen.
The plant uses the glucose for energy to grow. The oxygen is released back into
the air, which is why plants are so important for our atmosphere.
```

**Example 2 - Good Summary:**
```
Plants use photosynthesis to make their own food. They combine sunlight, water,
and carbon dioxide to create glucose for energy. As a bonus, they release oxygen
that we breathe. This makes plants essential for life on Earth.
```

**Example 3 - Original Text:**
```
Benjamin Franklin was a famous American who lived from 1706 to 1790. He was
born in Boston and had many jobs during his life. He was a printer,
businessman, scientist, and statesman. Franklin invented the lightning rod,
which protects buildings during storms. He helped write the Declaration of
Independence. Franklin was also a diplomat who helped the United States make
peace with other countries. His face appears on the $100 bill today.
```

**Example 3 - Good Summary:**
```
Benjamin Franklin was an important American figure who worked as a printer,
businessman, scientist, and government official. He invented the lightning rod
and helped write the Declaration of Independence. Franklin was also a skilled
diplomat who helped establish the United States as a new nation.
```

**Now Your Turn:**
Write a few-shot prompt using these examples:

```
I need help summarizing texts for my class. Here's the style I want:

Example 1:
Original: [Text about solar system]
Summary: [Summary provided above]

Example 2:
Original: [Text about photosynthesis]
Summary: [Summary provided above]

Example 3:
Original: [Text about Benjamin Franklin]
Summary: [Summary provided above]

Now please summarize this text in the same style:
[NEW TEXT TO SUMMARIZE]
```

**Success Criteria for Your Summaries:**
- Summaries are 3-4 sentences (not too long, not one sentence)
- Key information is included
- Your own words are used (not copied from original)
- Less important details are left out
- Main idea is clear

---

### 9th Grade Level: Analysis Summary

**Goal:** Teach the AI to create summaries that include analysis, not just information.

**Task:** Create 3 examples showing summary + analysis pattern

**Example 1 - Original Text:**
```
The Treaty of Versailles ended World War I in 1919. It required Germany to pay
massive amounts of money as reparations and to give up territory. The treaty
was very harsh on Germany. Many historians believe these harsh terms made Germans
angry and resentful. This anger and resentment was an important cause of World War II.
```

**Example 1 - Summary with Analysis:**
```
Summary: The Treaty of Versailles ended World War I but imposed harsh reparations
and territorial losses on Germany.

Analysis: The treaty's severity was counterproductive. By punishing Germany so
severely, the treaty created widespread resentment among Germans. This resentment
became a driving force for World War II, making the treaty ultimately destructive
to European peace.
```

**Example 2 - Original Text:**
```
Shakespeare wrote plays in a time before modern English. His language includes
words we don't use anymore and grammar different from today. Scholars debate
whether Shakespeare's language makes his works harder to understand. Some argue
that the language is a barrier to modern audiences. Others say the language is
part of Shakespeare's genius and shouldn't be changed.
```

**Example 2 - Summary with Analysis:**
```
Summary: Shakespeare wrote in Early Modern English, which differs from contemporary
English in vocabulary and grammar, creating debate about accessibility.

Analysis: This debate reflects a larger tension in literature: balancing fidelity
to original language with accessibility to modern audiences. While older language
may pose initial challenges, Shakespeare's linguistic choices contribute to the
poetic power and cultural significance of his work. Updating the language might
make plays more accessible but risks losing the artistry that made them endure.
```

**Example 3 - Original Text:**
```
Renewable energy sources like solar and wind power are growing in popularity.
They are cleaner than fossil fuels and don't produce greenhouse gases. However,
renewable energy has limitations. Solar panels work only when the sun is shining,
and wind turbines need windy locations. Renewable energy is more expensive to set
up initially. But as technology improves, these costs are dropping. Many experts
believe renewable energy will be a major part of our energy future.
```

**Example 3 - Summary with Analysis:**
```
Summary: Renewable energy sources offer environmental benefits but face challenges
related to reliability, location limitations, and initial costs.

Analysis: While renewable energy presents real drawbacks, these obstacles appear
surmountable. Decreasing costs and improving technology suggest that infrastructure
challenges are temporary rather than permanent. The environmental imperative to
reduce greenhouse gas emissions suggests that addressing renewable energy's
limitations is more practical than ignoring them.
```

**Now Your Turn:**
Write a few-shot prompt using these examples:

```
I'm learning to write summaries that include analysis. I want to show both
what a text says AND what it means. Here are examples:

Example 1:
Original: [Text about Treaty of Versailles]
Summary with Analysis:
Summary: [Summary provided above]
Analysis: [Analysis provided above]

Example 2:
Original: [Text about Shakespeare's language]
Summary with Analysis:
Summary: [Summary provided above]
Analysis: [Analysis provided above]

Example 3:
Original: [Text about renewable energy]
Summary with Analysis:
Summary: [Summary provided above]
Analysis: [Analysis provided above]

Now please write a summary with analysis for this text:
[NEW TEXT]
```

**Success Criteria for Your Summaries:**
- Summary is 1-2 sentences capturing main idea
- Analysis is 1-3 sentences exploring implications
- Analysis goes beyond the text (adds interpretation)
- The two parts are clearly separated
- Analysis shows critical thinking

---

### 11th Grade Level: Scholarly Summary

**Goal:** Teach the AI to create summaries that engage with scholarly arguments.

**Task:** Create 3 examples showing scholarly summary pattern

**Example 1 - Original Text:**
```
Historian Frederick Jackson Turner argued that the American frontier shaped
American identity and values. He claimed the frontier's emphasis on
individualism and self-reliance became core American traits. Turner's "frontier
thesis" was hugely influential in the early 20th century. However, modern
historians have criticized Turner's thesis. They point out that Turner ignored
Native Americans and treated the frontier as empty land. They also question
whether frontier values really shaped American identity as much as Turner claimed.
Recent scholarship emphasizes the violent displacement of Native peoples and the
frontier as a place of conflict, not opportunity.
```

**Example 1 - Scholarly Summary:**
```
Turner's frontier thesis posits that westward expansion created distinctly American
values of individualism and self-reliance. While profoundly influential in
establishing a national narrative, contemporary historians have substantially
problematized this interpretation through three critiques: the erasure of Native
American agency and presence, the assumption of empty/available land, and the
overestimation of frontier influence on American identity. Current scholarship
reconceptualizes the frontier as a contested space defined by violent dispossession
and indigenous resistance rather than triumphalist expansion.
```

**Example 2 - Original Text:**
```
Literary theorist Mikhail Bakhtin introduced the concept of "dialogism" - the
idea that meaning in literature comes from the interaction of different voices
and perspectives. Bakhtin argued that novels contain multiple voices in dialogue,
each with equal validity. He contrasted this with "monologism," where one voice
dominates. Bakhtin saw the novel form as inherently dialogic. Some critics have
extended Bakhtin's ideas to understand how literature reflects social dynamics.
Others have questioned whether all novels are truly dialogic or whether some
authors do dominate their texts.
```

**Example 2 - Scholarly Summary:**
```
Bakhtin's concept of dialogism proposes that literary meaning emerges through
the polyphonic interaction of multiple discursive voices within a text. This
theoretical framework—which privileges heteroglossia and resists authorial
monologism—has been productively applied to analyze how literary texts reflect
and constitute social relations. However, subsequent scholars have contested the
universality of Bakhtin's dialogic model, arguing that certain narrative
strategies and authorial techniques establish a hierarchy of voices that
constrains dialogic exchange.
```

**Example 3 - Original Text:**
```
Some scientists argue that consciousness arises from quantum processes in the
brain, particularly in microtubules within neurons. This view challenges the
dominant physicalist view that consciousness emerges from classical neural
computation. Supporters cite quantum effects in biology and note that classical
computation doesn't easily explain subjective experience. Critics counter that
quantum effects in the brain are unlikely and that there's no evidence quantum
processes contribute to consciousness. They argue that classical neural models
better explain current neuroscientific data. The debate remains unsettled.
```

**Example 3 - Scholarly Summary:**
```
The quantum consciousness hypothesis postulates that quantum mechanical processes,
particularly in neuronal microtubules, constitute the physical substrate of
consciousness and thereby account for phenomenal experience. Proponents argue
this framework addresses explanatory gaps in classical neural models and cites
evidence of quantum effects in biological systems. However, the dominant
physicalist consensus maintains that this hypothesis lacks empirical support and
posits unnecessary complexity; current neuroscientific evidence indicates classical
neural mechanisms are sufficient to explain observable cognitive phenomena. This
theoretical divide reflects broader disagreements about explanatory adequacy and
the criteria for evaluating theories of consciousness.
```

**Now Your Turn:**
Write a few-shot prompt for scholarly summarization:

```
I'm writing academic summaries that engage with scholarly arguments and debate.
I want to present claims, evidence, counterarguments, and current status. Here are examples:

Example 1:
Original: [Text about Turner's frontier thesis]
Scholarly Summary: [Summary provided above]

Example 2:
Original: [Text about Bakhtin's dialogism]
Scholarly Summary: [Summary provided above]

Example 3:
Original: [Text about quantum consciousness]
Scholarly Summary: [Summary provided above]

Now please write a scholarly summary for this academic text:
[NEW TEXT]
```

**Success Criteria for Your Summaries:**
- Argument is stated clearly and precisely
- Multiple perspectives are represented
- Evidence or reasoning for positions is shown
- Counterarguments are included
- Current scholarly consensus (or lack thereof) is noted
- Language is appropriate for academic context

---

## Exercise 2: Problem-Solving Format - Teaching a Method

**Scenario:** You want the AI to solve problems in a specific format.

### Problem Type: Mathematical Word Problems

**Goal:** Create consistent step-by-step solutions with clear reasoning

**Example 1:**
```
Problem: A backpack costs $45 and is on sale for 20% off. What is the sale price?

Model Solution Format:
Given Information: Original price = $45, Discount = 20%
Step 1: Calculate discount amount
  Discount = 20% × $45 = 0.20 × $45 = $9
Step 2: Subtract discount from original price
  Sale price = $45 - $9 = $36
Answer: The sale price is $36
Check: 20% off means paying 80%, and 80% × $45 = $36 ✓
```

**Example 2:**
```
Problem: If 3 apples cost $2.40, how much do 7 apples cost?

Model Solution Format:
Given Information: 3 apples cost $2.40, Need to find cost of 7 apples
Step 1: Find the cost per apple
  Cost per apple = $2.40 ÷ 3 = $0.80 per apple
Step 2: Multiply to find cost of 7 apples
  Cost of 7 apples = $0.80 × 7 = $5.60
Answer: 7 apples cost $5.60
Check: If 7 apples cost $5.60, then 3 apples should cost $2.40
  $5.60 ÷ 7 = $0.80 per apple; $0.80 × 3 = $2.40 ✓
```

**Example 3:**
```
Problem: A rectangle has a length of 12 meters and a width of 8 meters.
What is its perimeter?

Model Solution Format:
Given Information: Length = 12 meters, Width = 8 meters
Step 1: Recall the perimeter formula
  Perimeter = 2(length) + 2(width) or P = 2L + 2W
Step 2: Substitute the values
  P = 2(12) + 2(8)
Step 3: Calculate
  P = 24 + 16 = 40 meters
Answer: The perimeter is 40 meters
Check: Add all four sides: 12 + 8 + 12 + 8 = 40 ✓
```

**Your Few-Shot Prompt:**
```
I want you to solve word problems in a specific format. Here are examples:

Example 1:
Problem: A backpack costs $45 and is on sale for 20% off. What is the sale price?
[Solution format shown above]

Example 2:
Problem: If 3 apples cost $2.40, how much do 7 apples cost?
[Solution format shown above]

Example 3:
Problem: A rectangle has a length of 12 meters and a width of 8 meters.
What is its perimeter?
[Solution format shown above]

Now solve this problem in the same format:
[NEW PROBLEM]
```

**Success Criteria:**
- All given information is listed
- Steps are numbered and clear
- Formulas are shown before use
- Calculations are shown (not just answers)
- Answer is clearly stated
- Check shows the answer is reasonable

---

### Problem Type: Literary Analysis Questions

**Goal:** Teach consistent analysis format

**Example 1:**
```
Question: Analyze how the author uses vivid imagery to develop the theme
of isolation in this passage.

Model Answer Format:
Thesis Statement: The author employs sensory imagery to emphasize the
protagonist's emotional and physical isolation.

Body Paragraph 1:
Textual Evidence: [Quote from text]
Analysis: This imagery of _______ contributes to the theme because _________.
It shows the reader _________.

Body Paragraph 2:
Textual Evidence: [Different quote showing a pattern]
Analysis: Similarly, _________ reinforces the isolation theme by _________.
The progression from [first image] to [second image] shows _________.

Conclusion: Through consistent use of _________ imagery, the author creates
a palpable sense of isolation. This technique allows readers to _________.
```

**Example 2:**
```
Question: Explain how characterization reveals the protagonist's internal conflict.

Model Answer Format:
Thesis: [Character's name] embodies an internal conflict between _________
and _________, revealed through [method: dialogue/action/description].

Supporting Analysis:
Evidence 1: [Specific action/quote showing one side of conflict]
Interpretation: This shows the protagonist values _________ because _________.

Evidence 2: [Specific action/quote showing opposing impulse]
Interpretation: Yet the protagonist also _________, revealing conflict with _________.

Evidence 3: [Show how character attempts to resolve conflict]
Interpretation: The character's _________ demonstrates _________.

Synthesis: The character's internal conflict is significant because it
_________ and suggests the author's view that _________.
```

**Your Few-Shot Prompt:**
```
I'm practicing literary analysis. I want my answers to follow a specific structure:
clear thesis, supporting evidence with analysis, and meaningful conclusions.

Here are two examples of the format:

Example 1:
Question: Analyze how the author uses vivid imagery to develop the theme
of isolation in this passage.
Model Answer: [Format shown above with detailed example]

Example 2:
Question: Explain how characterization reveals the protagonist's internal conflict.
Model Answer: [Format shown above with detailed example]

Now answer this literary analysis question in the same format:
[NEW QUESTION]

Here's the relevant text: [PASSAGE]
```

**Success Criteria:**
- Clear thesis statement at beginning
- Multiple pieces of evidence from text
- Analysis explains HOW evidence supports interpretation
- Observations are specific (not vague)
- Conclusion ties evidence to larger meaning
- Format is consistent with models

---

## Exercise 3: Pattern Recognition - Teaching Through Examples

**Scenario:** You want the AI to recognize and apply a pattern from examples.

### 7th Grade: Identifying Parts of Speech

**Goal:** Show the AI the pattern of identifying parts of speech with explanations

**Example 1:**
```
Sentence: "The quick brown fox jumps over the lazy dog."

Pattern Recognition Response:
The (article) quick (adjective describing fox) brown (adjective describing fox)
fox (noun) jumps (verb - action) over (preposition) the (article) lazy
(adjective describing dog) dog (noun).

Explanation: Articles are words that go with nouns. Adjectives describe nouns.
Verbs are action words. Prepositions show location or direction.
```

**Example 2:**
```
Sentence: "She carefully walks through the tall grass."

Pattern Recognition Response:
She (pronoun) carefully (adverb - describes how the action happens) walks
(verb - action) through (preposition) the (article) tall (adjective) grass (noun).

Explanation: Pronouns replace nouns. Adverbs modify verbs and end in -ly.
The verb "walks" shows what she does. Prepositions show location.
```

**Example 3:**
```
Sentence: "Yesterday, Emma played happily in the park."

Pattern Recognition Response:
Yesterday (adverb - tells when) Emma (noun - proper name) played (verb - past
tense action) happily (adverb - describes how) in (preposition) the (article)
park (noun).

Explanation: Adverbs can show when something happens. Proper nouns name specific
people or places. The adverb "happily" describes HOW she played.
```

**Your Few-Shot Prompt:**
```
I want to practice identifying parts of speech. Here's how I want the answers:

Example 1: [Sentence with labeled words and brief explanation]
Example 2: [Sentence with labeled words and brief explanation]
Example 3: [Sentence with labeled words and brief explanation]

Please identify the parts of speech in this sentence the same way:
[NEW SENTENCE]
```

---

### 9th Grade: Identifying Sentence Types

**Goal:** Show how to categorize sentence types and explain their purpose

**Example 1:**
```
Sentence: "What time does the movie start?"

Sentence Type: Interrogative (question)
Purpose: Asks for information
Punctuation: Question mark (?)
Grammar Pattern: Verb comes before or early in the sentence (inverted order)
Example of Response: This asks a factual question that requires an answer.
```

**Example 2:**
```
Sentence: "Please turn off the lights when you leave."

Sentence Type: Imperative (command)
Purpose: Requests action from the reader/listener
Punctuation: Period (.) or exclamation point (!)
Grammar Pattern: Verb comes first; understood subject is "you"
Example of Response: This gives a polite command or instruction.
```

**Example 3:**
```
Sentence: "The sunset was so beautiful that everyone stopped to watch it."

Sentence Type: Complex declarative (statement with dependent clause)
Purpose: States a fact; explains relationship between ideas
Punctuation: Period (.)
Grammar Pattern: Contains a main clause and a dependent clause connected by "that"
Example of Response: This statement establishes a cause-effect relationship,
showing why people stopped watching.
```

**Your Few-Shot Prompt:**
```
I'm learning to identify and explain sentence types. I want to show the type,
its purpose, and how I can tell. Here are examples:

Example 1: [Sentence with type and explanation]
Example 2: [Sentence with type and explanation]
Example 3: [Sentence with type and explanation]

Please identify and explain the sentence type for this sentence:
[NEW SENTENCE]
```

---

### 11th Grade: Identifying Rhetorical Strategies

**Goal:** Show how to identify rhetorical techniques and analyze their effect

**Example 1:**
```
Passage: "We have nothing to fear but fear itself."

Rhetorical Strategy: Epimone (emphatic repetition)
Effect: By repeating "fear," the speaker emphasizes that fear itself—not external
threats—is the true obstacle. The parallelism and alliteration (fear/fear) create
a memorable, quotable statement.
Textual Analysis: This line appeared in FDR's inaugural address during the Great
Depression. The strategy transforms a vague concept (fear) into a concrete enemy
to overcome, thereby empowering listeners.
```

**Example 2:**
```
Passage: "The room was a hurricane of papers, books, and forgotten dreams."

Rhetorical Strategy: Metaphor with personification
Effect: By comparing the room to a hurricane, the writer conveys chaos and
destruction. Calling the books "forgotten dreams" personifies abstract concepts
as concrete objects with emotional weight.
Textual Analysis: This metaphor effectively conveys not just physical disorder
but emotional abandonment, suggesting the room owner's psychological state.
```

**Example 3:**
```
Passage: "We've invested decades in this program. Will we abandon it now?
Can we really turn our backs on the progress we've made?"

Rhetorical Strategy: Rhetorical questions with anaphora
Effect: These questions don't demand answers; instead, they guide the audience
toward a predetermined conclusion. The repetition of "will we / can we"
emphasizes commitment and moral obligation.
Textual Analysis: By posing as questions what are really statements, the speaker
avoids confrontation while still persuading. Listeners feel they've arrived at
the conclusion independently.
```

**Your Few-Shot Prompt:**
```
I'm analyzing rhetorical strategies in texts. I want to identify the strategy,
explain its immediate effect, and analyze its function in context. Here are examples:

Example 1: [Passage with strategy, effect, and analysis]
Example 2: [Passage with strategy, effect, and analysis]
Example 3: [Passage with strategy, effect, and analysis]

Identify and analyze the rhetorical strategy in this passage:
[NEW PASSAGE]
```

---

## Exercise 4: Combining Few-Shot with Other Techniques

**Scenario:** Few-shot prompting works even better when combined with other methods.

### Few-Shot + Multi-Step

**Goal:** Show examples AND ask for step-by-step breakdown

**Example Prompt:**
```
I want help organizing my essay. Here are examples of how I want my essays structured:

Example 1: Essay about [topic]
I. Introduction
   A. Hook: [specific example]
   B. Background: [context]
   C. Thesis: [main argument]
II. Body Paragraph 1
   A. Topic sentence: [main idea]
   B. Evidence: [specific example]
   C. Analysis: [explanation of evidence]
III. Body Paragraph 2
   [Similar structure]
IV. Conclusion
   A. Restatement of thesis
   B. Broader implications

I'm writing an essay about [MY TOPIC].

Please help me organize it step by step:
Step 1: Help me write a strong thesis statement
Step 2: Identify 2-3 main points I should cover
Step 3: Show me what evidence I should look for
Step 4: Outline my essay using the structure shown above
```

---

### Few-Shot + Constraints (Negative Prompting)

**Goal:** Show examples of what TO DO and what NOT TO DO

**Example Prompt:**
```
I want my summaries to be concise and clear. Here's what I want:

Good Example (clear and focused):
"The article discusses how climate change affects ocean temperatures and species
migration patterns. Rising temperatures cause fish populations to move to cooler
waters, disrupting traditional fishing industries."

Poor Example (too long/unfocused):
"This article is about climate change and how it affects the ocean in many ways.
The ocean is very big and has lots of fish and other creatures in it. The article
talks about how fish are moving because it's getting warmer. This is bad for
people who fish. There are many reasons for climate change."

Key Differences:
- Good: Specific facts, 2-3 sentences
- Poor: General statements, rambling, too long

Now write a summary of this text following the good example pattern:
[TEXT TO SUMMARIZE]

Remember: Be specific, be concise, avoid repeating information.
```

---

## Creating Effective Few-Shot Examples: Checklist

Before using few-shot prompting, make sure your examples:

**Quality Checklist:**
- [ ] Examples are clearly labeled (Example 1, Example 2, Example 3)
- [ ] Examples show variation (different topics, slightly different complexity)
- [ ] Examples demonstrate your exact desired format
- [ ] Examples are realistic (similar to what you'll actually ask for)
- [ ] Examples are high quality (show your best work, not mediocre work)
- [ ] Examples show common pitfalls (optional: show good vs. bad)

**Consistency Checklist:**
- [ ] All examples follow the same structure/format
- [ ] Tone is consistent across examples
- [ ] Length is similar across examples
- [ ] Level of detail is consistent
- [ ] Vocabulary level matches target

**Clarity Checklist:**
- [ ] It's obvious what's an example and what's the request
- [ ] Input and output are clearly separated
- [ ] Format differences would be visible to the AI
- [ ] New request is similar to examples (but different content)

---

## Reflection Questions

After practicing few-shot prompting:

- How did showing examples change the AI's response compared to just asking?
- Which subjects or tasks work best with few-shot prompting?
- How many examples do you actually need (2, 3, or more)?
- What happens if your examples are inconsistent?
- How does few-shot prompting compare to written instructions?
- Can you combine few-shot with other techniques you've learned?
- How can you use this in different classes?
