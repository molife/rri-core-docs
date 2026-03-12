# Agent Map

This document explains the roles of all agents in the Rays Operations system.

The system is built as a multi-agent architecture where each agent has a specific responsibility.

Core Control Agents

orchestrator-agent  
Routes requests to the correct specialist agent.

supervisor-agent  
Assigns agents to projects and coordinates multi-agent workflows.

system-agent  
Manages system memory, summaries, and long-term context to reduce token usage.

Project Setup Agents

research-agent  
Evaluates new ideas, researches opportunities, compares options, and identifies risks.

project-architect-agent  
Designs the structure of new projects including folders, files, platforms, documentation, and workflow phases.

builder-agent  
Creates the technical execution layer including code, websites, agent files, project scaffolds, APIs, and dashboards.

Specialist Agents

ministry-agent  
Handles ministry communication, grant writing, donors, volunteers, Mailchimp, outreach, blog content, and ministry platform content.

operations-agent  
Organizes tasks, workflows, execution steps, project boards, timelines, and operational structure.

business-agent  
Supports ecommerce, brand growth, affiliate marketing, product development, websites, marketing strategy, and monetization systems.

investments-agent  
Handles investment strategies including stocks, crypto, futures, forex, real estate investments, portfolio planning, and income systems.

legal-agent  
Handles legal structure including registrations, contracts, compliance, trademarks, nonprofit documentation, and real estate legal paperwork.

Agent Workflow Order

Typical project flow follows this sequence:

1 Research phase  
research-agent evaluates the idea.

2 Architecture phase  
project-architect-agent structures the project.

3 Supervision phase  
supervisor-agent assigns the correct agents.

4 Build phase  
builder-agent creates the system, code, or website.

5 Specialist execution  
specialist agents perform their domain tasks.

6 Memory storage  
system-agent stores summaries and project context.

7 Operations tracking  
operations-agent manages execution and workflow tracking.

Purpose of the System

The goal of this system is to:

reduce confusion across projects  
assign the correct expertise to each task  
maintain organized project structure  
reduce token waste through memory storage  
support ministry, business, investment, legal, and technology work in one coordinated system
