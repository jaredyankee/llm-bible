# the-man.md

*llm-bible for man*  

## 1. Establishing Context  
Begin every new conversation with context relevant to the topic of discussion.

**Why:** Without context the model wastes tokens searching for relevance it doesn't have to infer. A new conversation is a clean slate, use it.

1. Vague prompts get vague responses
  - Without context the model fills in gaps with assumptions
2. Correction turns are expensive
  - Bad assumption + Clarifying Exchange = 3x token usage
3. Models hallucinate confidently into ambiguity
  - The less you give it, the more it invents, and it won't tell you it's guessing

**Example**

❌ [Bad Prompt] 
> 💬 *real prompt from the author*
```
we talked about making like an LlmBible with all the little tips and tricks for using LLMs in code, must have snippets etc. Do you think i should get llmbible.ai or llmmd.ai for the domain?
```

✅ [Good Prompt]   
```
I am working on a project that will serve as an open-source repository and resource for LLM prompting best practices. I am trying to decide between llmbible.ai and llmmd.ai.
```

### Reference

Anthropic sent me an email with some basic considerations you learned in 1st grade. Turns out it works for AI too:

**Who**  
Tell Claude about yourself if it's relevant (“I'm a marketing manager working on a campaign”)

**What**  
Be specific about your task ("I need to write a blog post about sustainable fashion")

**Why**  
Share your goals ("This needs to appeal to Gen Z customers")

**How**  
Mention any preferences ("Keep it under 500 words and include statistics")
