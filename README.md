# agnoai-agent-design-demo
This is a conceptual demo showing how I would design a multi-agent system inspired by [AgnoAI]([https://docs.agno.com/introduction]), using YAML configuration, planner roles, and tool integrations.

##  Goal
Design an LLM-powered research assistant that:
- Searches academic databases (e.g., arXiv)
- Summarizes relevant findings
- Stores summaries in vector memory
- Delegates follow-up questions to a secondary agent

##  Key Concepts from AgnoAI
- **Agents** are defined in YAML
- **Planner** coordinates agent actions
- **Memory** enables context persistence
- **Tools** are APIs or scripts the agents can call

## 📁 Files
- `research-agent.yaml`: YAML config for a research agent
- `planner-flow.jpg`: diagram showing agent orchestration flow

##  Use Case Example
> A user asks: “Find the latest LLM papers about medical imaging.”
1. `ArxivFetcher` pulls matching titles from arXiv
2. `Summarizer` creates concise summaries
3. Summaries are stored in memory for later querying
