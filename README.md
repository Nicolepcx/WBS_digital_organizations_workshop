# WBS – Agent Infrastructure for Digital Organizations

Code and notebooks for the WBS workshop on building, scaling, and securing agentic systems for finance workflows.

## Workshop Outline

- **Part 1 — Why agent infrastructure matters:** adoption versus impact, horizontal copilots versus vertical workflow transformation.
- **Part 2 — Finance workflows and task decomposition:** which finance tasks are agent suitable and why.
- **Part 3 — Topology choice:** single agent, supervisor, hierarchical, independent, hybrid, mapped to finance use cases.
- **Part 4 — Reliability in production:** coordination tax, retries, latency, validation gates, correction loops.
- **Part 5 — Threat modeling for agent systems:** layered threat model, CIA mapping, model → orchestration → tool → memory propagation.
- **Part 6 — Production controls:** guardrails, red teaming, memory controls, HITL, observability, governance.

## Notebooks

Every notebook can be opened and run on Google Colab directly from the links below. Just click the **Open In Colab** badge next to the notebook you want to run.

### Part 1 — Why Agent Infrastructure Matters

| Notebook | Colab |
|---|---|
| Prompt → Context → Harness Progression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/prompt_context_harness_progression.ipynb) |
| Harness Components | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/harness_components.ipynb) |
| Intro to LangGraph | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/intro_langgraph.ipynb) |
| LLM State | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/LLM_state.ipynb) |
| State Across Execution Boundaries | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/state_across_execution_boundaries.ipynb) |

### Part 2 — Finance Workflows and Task Decomposition

| Notebook | Colab |
|---|---|
| Chain-of-Thought (CoT) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/CoT.ipynb) |
| LangGraph Research (OpenAI) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/Langgraph_research_OAI.ipynb) |
| LangGraph Extract Signals (OpenAI) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/Langgraph_extract_signals_OAI.ipynb) |
| News Summarizer with Exa | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/news_summarizer_with_Exa.ipynb) |
| LATS Advice (Language Agent Tree Search) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/lats_advice.ipynb) |

### Part 3 — Topology Choice

| Notebook | Colab |
|---|---|
| Multi-Agent Investment Analysis (Supervisor) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/LangGraph_multi_agents_investment_analysis_supervisor.ipynb) |
| Hierarchical Agent Teams | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/hierarchical_agent_teams.ipynb) |
| Swarms | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/swarms.ipynb) |
| Communication Patterns | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/communication_patterns.ipynb) |
| Research Context: Subagents + Supervisor | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/research_context_subagents_supervisor.ipynb) |

### Part 4 — Reliability in Production

| Notebook | Colab |
|---|---|
| Pydantic Agent Consistency | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/pydantic_agent_consistency.ipynb) |
| LangGraph Logging & Checkpointing | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/Langgraph_logging_checkpointing.ipynb) |
| Model Fallback | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/model_fallback.ipynb) |
| Hardening Backbone | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/hardening_backbone.ipynb) |
| Inference Backends | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/inference_backends.ipynb) |
| Agent Cost Estimator by Topology | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/agent_cost_estimator_based_on_topology.ipynb) |
| Memory Footprint, Throughput & GPU Requirements | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/memory_footprint_throughput_and_GPU_requirements.ipynb) |
| Memoizing Swarm Research Engine | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/memoizing_swarm_research_engine.ipynb) |

### Part 5 — Threat Modeling for Agent Systems

| Notebook | Colab |
|---|---|
| OWASP ASI 2026 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/OWASP_ASI_2026.ipynb) |

### Part 6 — Production Controls

| Notebook | Colab |
|---|---|
| LlamaFirewall | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/LlamaFirewall.ipynb) |
| A2A + MCP Governed | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/A2A_MCP_Governed.ipynb) |
| LangGraph + E2B Sandbox | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/langgraph_E2B.ipynb) |
| Programmatic Tool Calling (Monty) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/programmatic_tool_calling_monty.ipynb) |
| MCP Server with Composio | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/server_composio.ipynb) |
| Human-in-the-Loop (HITL) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/HITL.ipynb) |
| LangGraph Memory Types | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/langgraph_memory_types.ipynb) |
| LangGraph Episodic & Procedural Memory | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/langgraph_episodic_procedural.ipynb) |
| LangGraph Episodic & Procedural Memory (Tools) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/langgraph_episodic_procedural_tools.ipynb) |
| External Evaluation Pipelines (Langfuse) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/external_evaluation_pipelines_Langfuse.ipynb) |
| External Evaluation Pipelines (LangSmith) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/WBS_digital_organizations_workshop/blob/main/external_evaluation_pipelines_langsmith.ipynb) |

__NOTE:__ You may need to run the notebooks with a GPU.
