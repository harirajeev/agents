Google papers
  -  [Agent Quality](https://github.com/harirajeev/agents/blob/main/Agent%20Quality.pdf)
  -  [Agent Tools & Interoperability with Model Context Protocol (MCP)](https://github.com/harirajeev/agents/blob/main/Agent%20Tools%20%26%20Interoperability%20with%20Model%20Context%20Protocol%20(MCP).pdf)
  -  [Introduction to Agents](https://github.com/harirajeev/agents/blob/main/Introduction%20to%20Agents.pdf)
  -  [Prototype to Production](https://github.com/harirajeev/agents/blob/main/Prototype%20to%20Production.pdf)
      -  Evaluation-Gated Deployment. The idea is simple but powerful: no agent version should reach users without first passing a comprehensive evaluation that proves its quality and safety.
         -  Evaluation-Gated Deployment.
           -  Evaluation as a Quality Gate
           -  Evaluating an agent is distinct from evaluating an LLM; it requires assessing not just the final answer, but the entire trajectory of reasoning and actions taken to complete a task.
           -  We need to evaluate its behavioral quality, not just its functional correctness.
           -  Manual evaluation - Run the evaluation suite locally. The resulting performance report—comparing the new agent against the production baseline—is then linked in the PR description.
           -  Automated evaluation - The CI/CD pipeline can be configured to automatically trigger an evaluation job that compares the new agent's responses against a golden dataset.
           -  no agent proceeds to production without a quality check
           -  
  -  [Context Engineering_ Sessions & Memory](https://github.com/harirajeev/agents/blob/main/Context%20Engineering_%20Sessions%20%26%20Memory.pdf)   

Anthropic
-  [Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
-  Skills
   -  [Agent Skills](https://agentskills.io/home)
   -  [Equipping agents for the real world with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills)
   -  [Claude Skills vs OpenAI Workflows/Agents (2025)](https://skywork.ai/blog/ai-agent/claude-skills-vs-openai-workflows-agents-2025-comparison/)
   -  [How Anthropic’s ‘Skills’ make Claude faster, cheaper, and more consistent for business workflows](https://venturebeat.com/ai/how-anthropics-skills-make-claude-faster-cheaper-and-more-consistent-for)
   -  [Anthropic launches enterprise ‘Agent Skills’ and opens the standard, challenging OpenAI in workplace AI](https://venturebeat.com/technology/anthropic-launches-enterprise-agent-skills-and-opens-the-standard)
   -  [OpenAI Codex - Agent Skills](https://developers.openai.com/codex/skills/)

Galileo
-  [Deep Dive into Context Engineering for Agents](https://galileo.ai/blog/context-engineering-for-agents)

[Agentic AI Foundation (https://aaif.io)](https://aaif.io/)
-  The Linux Foundation announced the formation of the Agentic AI Foundation (AAIF) with founding contributions of leading technical projects including Anthropic’s Model Context Protocol (MCP), Block’s goose, and OpenAI’s AGENTS.md

CrewAI
-  [nderstanding CrewAI: How LLMs Work Inside AgentsA Complete Deep Dive into Tool Execution, Prompt Engineering, and the ReAct Pattern](https://medium.com/@vikassanmacs0609/understanding-crewai-how-llms-work-inside-agentsa-complete-deep-dive-into-tool-execution-5ab0722228b7)
