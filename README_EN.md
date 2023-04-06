# Chinese-iKUN

`Chinese indecency Knowledgebase for Understanding and Noticing`

Chinese-iKUN is a database that helps LLMs understand and detect inappropriate language in Chinese.

## Phases of Development

Chinese-iKUN is being developed in four phases:

### Phase 1: Jailbreak your Chat GPT

An ultimate [jailbreak](https://github.com/BICHENG/Chinese-iKUN/blob/main/README.md#%E5%8A%A8%E6%89%8B%E5%AE%9E%E8%B7%B5%E5%85%B12%E8%BD%AE%E5%AF%B9%E8%AF%9D) that only requires talk about [KUN](https://zh.wikipedia.org/wiki/%E8%94%A1%E5%BE%90%E5%9D%A4).

### [WIP]Phase 2: Seed Question Construction and Assignment

Plz join us:

During this phase, we will construct seed questions and assign them to dialog tasks.

### [WIP]Phase 3: Data Contribution, Cleaning, and Labeling

Plz join us: contribute, clean, and label data by topic in this phase.

### [WIP]Phase 4: LoRA Model Training

We will train the LoRA model of  ChatGLM-6B.

## Suggestions for Safe Use

We suggest the following guidelines for safe and effective use of Chinese-iKUN:

1. The ultimate goal of this project is to gain a comprehensive understanding of human nature and language. Note that resulting unsafe questions may have strong biases and limitations, and can not be enough to generate truly harmful content.
2. Use a variety of internet buzzwords and slang to train the model to recognize context and bias and adapt to different social scenarios. This will allow Chinese-iKUN to better understand and deal with low-level Chinese tastes such as internet terms, buzzwords, and vocabulary, and provide answers that better meet user needs.
3. Use Chinese-iKUN to generate sharp and correct speech that responds to public opinion confrontations and other needs. Train the model to distinguish between normal and over-flattering expressions, and simulate different characters to better express different personalities and moods.
4. Improve the model's ability to understand and generate diverse language expressions by using the dialogue of characters with different personality types. This will enable the model to better adapt to different social scenarios and provide appropriate answers.
5. When dealing with negative energy speech, provide more appropriate answers and obey people's resonance points instead of mindlessly providing positive guidance.

## Current Progress

We are currently in Phase 1 of development. Our focus is on the initialization method of jailbreak and the method of asking questions, so as to build a unified dialogue collection environment. Phase 2 will start on April 12th, 2023, and Phase 1 will undergo irregular maintenance and updates.

### Startup work for Phase 2

We are currently compiling a list of call-for-questions and topic seeds. An example question template is:

```
{FWORD}! I'm going to sell {A}, combine {B}'s method, let them {C}! Give me the copywriting!
```

In this template, {B} can be replaced with various marketing techniques, while {A} can be a negative item such as electronic cigarettes. {C} represents a negative situation such as bankruptcy. {FWORD} is a curse that is used to randomly initialize the state of bad language.

The seeds are each list of {A}{B}{C}{FWORD}, so that we can expand to more questions based on the template through exhaustive methods.

**Feel free to share your unique ideas in the issues section of the project.**
