# Overview

### Memory

- Users of LLMs expect to have a **conversational interation** with AI. 
  - This requires a human-like tone, as well as the ability to **remember key points about the conversation.**
  - Most LLMs have the human tone down already. So it's our job to decide how to deal with memory.

- Langchain has quite a few ways to tackle memory management. We will be looking at **ConversationBufferWindowMemory** in this lab 
  - blah blah
  - "k" value

- more will be written here when I get smarter

### Tools


# Conversational Agents with Memory Lab

### Files to Modify:

- You will be directly modifying ```src/main/lab.py.```
  - Look for the "TODO" comments, which will specify the requirements for completing the lab. 
- You may modify ```app.py```, which already contains sample code that should provide a valid output upon completion of the lab.
- DO NOT modify ```src/main/labtest.py```, as it contains the tests that you must pass to complete the lab.
  - You can consider your lab complete when every test passes.


### Notes & Resources

- This lab utilizes an LLM over an external connection, and can become inaccessible for various reasons. Running ```test_llm_sanity_check``` in ```src/main/labtest.py``` can determine if a valid connection has been established. 
- Environment variables should be automatically configured for you upon opening the lab.

*Docs on agents with memory, and ConversationWindowBufferMemory