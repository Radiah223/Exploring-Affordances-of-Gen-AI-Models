# Exploring-Affordances-of-Gen-AI-Models
We explore and assess how Large Language Models can reason spatial and interaction data through prompt design in order to connect users with LLMs to perform various tasks. <br>
<br>
Model used: GPT 3.5<br>


## Experiment 1: Assessing LLM reasoning for UI elements in HTML websites using small-scale experimentation 
We utilized the prompt structure proposed in <a href = "https://arxiv.org/abs/2209.08655"><em>Enabling Conversational Interaction with Mobile UI using Large Language Models</em></a> by Bryan Wang, Gang Li, and Yang Li and benchmarked GPT 3.5's performance in summarization, question-generation, question-answer (QA), and mapping instructions to UI elements to assess GPT 3.5's reasoning with UI elements in five static webpages with increasing complexity. Additionally we performed 0/1/2-shot prompting. <br> 
Overall results: GPT 3.5 provided accurate responses for summarization, question-generation and mapping instructions for all five webpages. However, for question-answer it hallucinates answers especially for more complex webpages. 

## Experiment 2: Re-assessing LLM reasoning for UI elements in HTML websites using DOM trees 

