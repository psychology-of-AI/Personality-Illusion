## Experimental Data 

This folder contains all data collected from self-reports and behavioral tasks, including both baseline responses and persona injection experiments described in our paper.  

## Structure 

* **[baseline_responses](baseline_responses)**  
  Contains the baseline results (default system prompt, no persona injection) for both self-reports and behavioral tasks. Specifically, it includes self-reports for 6 base models, 12 instruct models, and behavioral task results for 12 instruct models.  


* **[persona_injection](persona_injection)**  
  Contains the data for RQ3, where we injected personality trait personas to steer model behavior. Specifically:  
  - **[Agreeableness](persona_injection/agreeableness)**: injecting agreeableness personas and measuring self-reports and sycophancy.  
  - **[Self-regulation](persona_injection/self_regulation)**: injecting self-regulation personas and measuring self-reports and risk-taking.  
  Each was evaluated using three prompting strategies adapted from established LLM personality research. The corresponding data can be found in the respective subfolders.   