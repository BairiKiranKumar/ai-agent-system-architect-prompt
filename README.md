# AI Agent System Architect

A model-agnostic master prompt for designing practical AI-powered workflows and agent systems.

Instead of immediately creating multiple AI agents, this prompt first determines whether your workflow actually needs:

- deterministic automation
- one AI agent
- one agent with tools
- multiple specialized agents
- APIs
- human approval
- or a hybrid architecture

## What It Does

The prompt helps an AI analyze a real business or technical workflow and design:

- workflow architecture
- agent responsibilities
- task classification
- system prompts
- model requirements
- tool/API usage
- structured handoffs
- memory strategy
- human approval points
- guardrails
- failure recovery
- logging and observability
- cost optimization
- implementation roadmap

## Model Agnostic

The prompt is not tied to one provider.

You can use it with models from:

- OpenAI
- Anthropic
- Google
- xAI
- open-source/self-hosted models
- future model providers

The architecture is based on required capabilities rather than model brand.

## Philosophy

Don't create an AI agent when normal software can do the job better.

Prefer:

Deterministic automation → when rules are enough

One agent + tools → when reasoning is needed

Multiple agents → only when specialization provides a real advantage

Human review → for sensitive, expensive, or irreversible decisions

## Usage

1. Open [PROMPT.md](./PROMPT.md)
2. Copy the full prompt
3. Paste it into your preferred AI model
4. Describe the workflow you want to build

Example:

> I run a web development agency. I want to automate the workflow from client requirements through research, content, development, QA, and final delivery. Design the appropriate AI architecture.

The AI should first analyze the workflow before recommending an architecture.

## Example Output

A workflow might become:

Client Request
      ↓
Requirements Analysis
      ↓
Task Classification
      ↓
Automation / AI / Human
      ↓
Specialized AI Components
      ↓
Validation
      ↓
Human Approval
      ↓
Final Output