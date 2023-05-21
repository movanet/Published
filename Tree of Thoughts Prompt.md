---
share: true
---

Tags: #prompt #ChatGPT 


Someone at Reddit give a prompt based on the [Tree of Thoughts](https://arxiv.org/pdf/2305.10601.pdf) paper (see below) which I found to be quite helpful. 

```
Given the task: {**}, break it down into intermediate steps or 'thoughts'. Consider multiple different reasoning paths that could be taken to solve the task. Explore these paths individually, reflecting on the possible outcomes of each. Then, consider how you might backtrack or look ahead in each path to make global decisions. Based on this analysis, choose the next course of action.
```

I then asked ChatGPT (4) to read the paper and to generate the prompt based on the paper


**Prompt 1 - Problem Decomposition**:

```
ChatGPT, can you help me break down the problem of [insert problem] into smaller, manageable steps or 'thoughts'?

```

**Prompt 2 - Reasoning Paths**:

```

"ChatGPT, for the problem of [insert problem], what are the different reasoning paths we could take? Could you explore these paths individually and reflect on the possible outcomes of each?"

```

**Prompt 3 - Backtracking and Looking Ahead**:

```

ChatGPT, considering the problem of [insert problem], how might we backtrack or look ahead in our reasoning process to make global decisions?

```

**Prompt 4 - Decision Making**: 

```

ChatGPT, based on the analysis of the problem [insert problem], what would be the next best course of action?

```

**Prompt 5 - Reflection and Evaluation**:

```

 "ChatGPT, can you reflect on the solution we've generated for the problem [insert problem] and evaluate its effectiveness?"

```


I also asked it to merge all the prompts:


```
ChatGPT, I have a task for you [insert task]. Please perform the task by breaking down the problem into smaller steps, exploring different reasoning paths and their potential outcomes, backtracking or looking ahead to make global decisions, and finally reflecting on and evaluating the proposed solution.
```

