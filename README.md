# agnoai-agent-design-demo
This is a conceptual demo showing how I would design a multi-agent system inspired by [AgnoAI](https://github.com/Agno-Research/AgnoAI), using YAML configuration, planner roles, and tool integrations.

## ✨ Goal
Design an LLM-powered research assistant that:
- Searches academic databases (e.g., arXiv)
- Summarizes relevant findings
- Stores summaries in vector memory
- Delegates follow-up questions to a secondary agent

## 🧠 Key Concepts from AgnoAI
- **Agents** are defined in YAML
- **Planner** coordinates agent actions
- **Memory** enables context persistence
- **Tools** are APIs or scripts the agents can call

## 📁 Files
- `research-agent.yaml`: YAML config for a research agent
- *(optional)* `planner-flow.jpg`: diagram showing agent orchestration flow
