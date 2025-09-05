# how do you think like an llm?
Knowing simple concepts of what the LLM might be thinking is helpful for building ideas around prompt engineering and getting AI to do what you want it to do.

## beginning
LLM's think in tokens, and all they really know is what the most likely next token is!

For example, when you ask the LLM the famous question *how many R's are in the word strawberry*, it doesn't actually know anything about the letters! **Everything that the LLM "knows" is really just the LLM recalling from it's memory!**

So when it responds to your R's in strawberry question, it's just recalling from it's memory on the internet, *what have people said about the R's in strawberry?*

This concept can be applied to **everything**, even LLM reasoning!

A big part of the reason of why reasoning is so effective is because the LLM by normal LLM's fully rely on memory to think, unless there is special system prompting!

By allowing a model to reason, it can recall a bunch of little facts about details of the prompt and put them into the context window, so that this information is considered in the final response. Essentially in reasoning, the model creates a clearer context window for itself. You can think of reasoning somewhat as a web search tool call.
