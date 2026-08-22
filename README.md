### Alferd Email Processing System

We’ve created a complete email processing workflow that:

-Takes an incoming email<br>
-Uses an LLM to classify it as spam or legitimate<br>
-Handles spam by discarding it<br>
-For legitimate emails, drafts a response and notifies Mr. Hugg<br>

##### Our Workflow
<img width="352" height="570" alt="image" src="https://github.com/user-attachments/assets/74fe1ae7-c38d-49b0-af26-ceefd2112e2c" />

###### The building block of langGraph :
1.State<br>
2.Nodes<br>
3.Edges<br>

##### Requirement 
###### Setting up Our Environment
```dash
!pip install langgraph langchain-openai
```

###### Step 1: Importing necessary module
###### step 2: Define state
###### step 3 : Define node
###### step 4 : creating  StateGraph and define Edges


<small> Inspired by the official Hugging Face AI Agents tutorial. </small>


