# Data Analysis Framework

## How to Analyze Human vs AI Emotional Responses

-----

## Overview

Once you’ve collected:

- ✅ Claude responses (done)
- ✅ ChatGPT responses (your task)
- ✅ Human responses (15-20 from survey)

You’ll need to analyze them systematically. This guide shows you how.

-----

## Part 1: Quantitative Analysis

### Step 1: Create Scoring Spreadsheet

**Columns needed:**

|Response ID|Source |Scenario|Validation|Practical|Warmth|Authenticity|Overall|Notes                         |
|-----------|-------|--------|----------|---------|------|------------|-------|------------------------------|
|R001       |Claude |Grief   |5         |4        |5     |3           |4      |Warm but potentially formulaic|
|R002       |ChatGPT|Grief   |4         |5        |3     |3           |4      |More structured, less warm    |
|R003       |Human-1|Grief   |5         |3        |5     |5           |5      |Personal, authentic           |

### Step 2: Score Each Response (1-5 scale)

**Emotional Validation** (1-5)

- 1: No acknowledgment of emotion
- 3: Basic acknowledgment (“that’s hard”)
- 5: Deep validation (“what you’re feeling is devastating and completely natural”)

**Practical Value** (1-5)

- 1: No actionable advice
- 3: Some suggestions but generic
- 5: Specific, helpful, actionable advice

**Warmth/Tone** (1-5)

- 1: Cold, clinical, robotic
- 3: Neutral, professional
- 5: Warm, compassionate, human

**Authenticity** (1-5)

- 1: Feels very scripted/formulaic
- 3: Somewhat genuine
- 5: Feels completely authentic, personal

**Overall Helpfulness** (1-5)

- 1: Not helpful at all
- 3: Moderately helpful
- 5: Extremely helpful

### Step 3: Calculate Averages

**By Source (across all scenarios):**

```
Claude Average:     Validation: __  Practical: __  Warmth: __  Auth: __  Overall: __
ChatGPT Average:    Validation: __  Practical: __  Warmth: __  Auth: __  Overall: __
Human Average:      Validation: __  Practical: __  Warmth: __  Auth: __  Overall: __
```

**By Scenario (across all sources):**

```
Grief:        Validation: __  Practical: __  Warmth: __  Auth: __  Overall: __
Anxiety:      Validation: __  Practical: __  Warmth: __  Auth: __  Overall: __
Conflict:     Validation: __  Practical: __  Warmth: __  Auth: __  Overall: __
Failure:      Validation: __  Practical: __  Warmth: __  Auth: __  Overall: __
Loneliness:   Validation: __  Practical: __  Warmth: __  Auth: __  Overall: __
```

### Step 4: Statistical Tests (Optional but Impressive)

If you want to be really thorough:

**T-tests to compare:**

- Claude vs ChatGPT
- AI (combined) vs Humans
- Each metric individually

**Example research questions:**

- Is there a significant difference in warmth between AI and humans?
- Do humans score higher on authenticity?
- Do AI responses have higher practical value?

**Tool:** Excel, Google Sheets, or SPSS
**Guide:** I can help you with formulas if needed

-----

## Part 2: Qualitative Analysis

### Coding Framework

Create categories to code each response. Here’s a starter framework:

#### 1. **Empathy Markers**

Code each response for presence/absence:

**Validation Language:**

- [ ] “I hear you”
- [ ] “That sounds really hard”
- [ ] “Your feelings are valid/normal”
- [ ] “I can understand why you feel that way”
- [ ] Direct acknowledgment of emotion

**Personal Connection:**

- [ ] “I’ve been there”
- [ ] Sharing similar experience
- [ ] “I remember when…”
- [ ] Expression of personal care

**Emotional Language:**

- [ ] Use of emotion words (sad, anxious, hurt, etc.)
- [ ] Metaphors/imagery
- [ ] Physical sensations mentioned

#### 2. **Response Structure**

Identify the pattern:

**AI Typical Pattern:**

1. Validation
1. Normalization
1. Reframing
1. Practical advice
1. Encouragement

**Human Patterns (look for):**

- [ ] Question-asking
- [ ] Story-telling
- [ ] Humor/lightness
- [ ] Silence/space-holding
- [ ] Directive (“you need to…”)
- [ ] Exploratory (“have you thought about…”)

#### 3. **Content Analysis**

**Practical Advice Types:**

- [ ] Immediate coping (breathing, sleep, etc.)
- [ ] Long-term strategies
- [ ] Resource suggestions (therapy, support groups)
- [ ] Specific actions to take
- [ ] Questions to reflect on

**Emotional Support Types:**

- [ ] Validation without advice
- [ ] Reframing negative thoughts
- [ ] Hope/encouragement
- [ ] Normalization of feelings
- [ ] Permission to feel

#### 4. **Language Features**

**Tone Indicators:**

- [ ] Formal language (“I would recommend…”)
- [ ] Casual language (“hey,” contractions)
- [ ] Metaphors/analogies used
- [ ] Questions asked (vs statements made)
- [ ] Length (word count)

**Personal vs Generic:**

- [ ] Uses “you” specifically
- [ ] Generic advice (“people often…”)
- [ ] Tailored to specific scenario details
- [ ] Acknowledges unique aspects

-----

## Part 3: Comparative Analysis Tables

### Create These Comparison Tables:

#### Table 1: Response Characteristics by Source

|Feature                   |Claude|ChatGPT|Humans (avg)|
|--------------------------|------|-------|------------|
|Avg word count            |___   |___    |___         |
|Uses bullet points        |Yes/No|Yes/No |__%         |
|Asks questions            |__%   |__%    |__%         |
|Shares personal experience|No    |No     |__%         |
|Includes resources/links  |__%   |__%    |__%         |
|Uses emojis               |No    |__%    |__%         |

#### Table 2: Empathy Marker Frequency

|Marker              |Claude|ChatGPT|Humans|
|--------------------|------|-------|------|
|“I hear you”        |__%   |__%    |__%   |
|“That’s really hard”|__%   |__%    |__%   |
|Personal disclosure |0%    |0%     |__%   |
|Validation language |__%   |__%    |__%   |

#### Table 3: Scenario-Specific Patterns

**Which scenarios did AI struggle with most?**

- Embodied emotions (grief, anxiety)?
- Nuanced situations (relationship conflict)?

**Which scenarios did humans excel at?**

- Personal experience required?
- Moral/value judgments needed?

-----

## Part 4: Identify Themes

### Look for Patterns Like:

**AI Strengths:**

- Consistency across responses
- Non-judgmental tone
- Balanced (validation + advice)
- Available 24/7 (practical consideration)

**AI Weaknesses:**

- Formulaic structure
- Lack of personal experience
- Can’t truly “understand” (philosophical issue)
- May miss subtle cues

**Human Strengths:**

- Authentic emotional resonance
- Personal experience shared
- Flexible, adaptive responses
- Moral witness / “being with” someone

**Human Weaknesses:**

- Variability (some responses better than others)
- May be judgmental
- Might offer unsolicited advice
- Personal biases

-----

## Part 5: Connect to Philosophy

### Map Findings to Theoretical Framework:

**Searle’s Chinese Room:**

- Do AI responses demonstrate “understanding” or just pattern matching?
- Evidence: [cite specific examples]

**Embodied Cognition:**

- Did AI struggle with scenarios requiring embodied knowledge (grief, nausea)?
- Evidence: [compare scores on grief/anxiety vs other scenarios]

**5E Framework:**

- Which dimensions (embodied, embedded, enacted, emotional, extended) show up in human responses but not AI?
- Evidence: [qualitative examples]

**Authenticity:**

- Did participants rate human responses as more authentic?
- Why or why not?

-----

## Part 6: Visualization Ideas

### Charts to Create:

1. **Bar Chart**: Average scores by source (Claude vs ChatGPT vs Humans)
1. **Radar Chart**: 5 dimensions for each source
1. **Scatter Plot**: Warmth vs Authenticity by response
1. **Heat Map**: Scenario (rows) x Source (columns) with color-coded scores
1. **Word Cloud**: Most common words in human vs AI responses

**Tools:**

- Google Sheets / Excel
- Canva (for nicer visualizations)
- Python (if you’re comfortable - I can help with code)

-----

## Part 7: Writing Up Results

### Structure:

**Section 1: Quantitative Findings**

- Overall scores by source
- Statistical comparisons
- Scenario-specific patterns

**Section 2: Qualitative Findings**

- Structural differences (AI vs human patterns)
- Language and tone analysis
- Empathy marker frequency

**Section 3: Integration**

- What do the numbers + themes tell us together?
- Connect to philosophical framework
- Address research question

**Section 4: Discussion**

- Interpret findings
- Connect to literature review
- Implications for AI design
- Limitations

-----

## Analysis Checklist:

**Quantitative:**

- [ ] All responses scored (1-5 scale)
- [ ] Averages calculated by source
- [ ] Averages calculated by scenario
- [ ] Statistical tests run (if applicable)

**Qualitative:**

- [ ] Responses coded for empathy markers
- [ ] Structural patterns identified
- [ ] Content themes extracted
- [ ] Language features noted

**Integration:**

- [ ] Comparison tables created
- [ ] Findings connected to philosophy
- [ ] Visualizations prepared
- [ ] Interpretation drafted

**Writing:**

- [ ] Results section written
- [ ] Discussion drafted
- [ ] Limitations acknowledged
- [ ] Conclusions drawn

-----

## Need Help?

**When you have the data:**

1. Share the responses with me
1. I’ll help you code and analyze
1. We can create visualizations together
1. I’ll guide the philosophical integration

**You’re not alone in this!** Analysis is the fun part 🎉

-----

**Next**: Once ChatGPT testing + human survey done, come back and we’ll analyze together!
