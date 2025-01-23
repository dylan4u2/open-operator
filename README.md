# Open Operator

What will it take to make a versatile computer use agent that can safely and effectively handle any task?

This is a collection of resources and ideas towards this goal.

## Tasks to be Performed

1. **Code Development and Management**
   - Code generation and modification
   - Project setup and dependency management
   - Code refactoring and optimization
   - Version control operations
   - Documentation generation

2. **Data Processing and Management**
   - Data entry and extraction
   - Document processing and analysis
   - Data synchronization between applications
   - Database operations
   - Web scraping and data collection

3. **Workflow Automation**
   - Task scheduling and management
   - Email automation and processing
   - Customer support operations
   - Marketing activities
   - Financial operations

4. **Web and Browser Interactions**
   - Web navigation and form filling
   - Browser automation
   - API interactions
   - Web-based research
   - Content management

5. **System Operations**
   - File system operations
   - Environment setup
   - Software installation
   - System monitoring
   - Task automation

## Features

1. **AI-Powered Automation**
   - Natural language understanding
   - Task planning and execution
   - Adaptive learning from demonstrations
   - Context-aware decision making
   - Multi-step workflow automation

2. **User Interface Interaction**
   - Mouse and keyboard control
   - Screen analysis and understanding
   - Element recognition and interaction
   - Form filling and data input
   - Visual workflow builders

3. **Integration Capabilities**
   - API integration
   - Third-party service connections
   - Cross-platform compatibility
   - Custom node/component creation
   - Webhook support

4. **Development Tools**
   - Code editors
   - Terminal access
   - Browser integration
   - Version control
   - Debugging capabilities

5. **Security and Privacy**
   - Data protection measures
   - Access control
   - PII/PHI scrubbing
   - Secure API handling
   - Compliance features

## Benchmarks

### WebArena
[WebArena](benchmarks/webarena.md) is a realistic web environment for building autonomous agents. It creates websites from popular categories with functionality and data mimicking their real-world equivalents. Key features include:

- Standalone, self-hostable web environment
- Creates websites from four popular categories with realistic functionality
- Embeds tools and knowledge resources as independent websites
- Provides annotated programs for programmatically validating task correctness
- Supports task setup and execution-based evaluation

### OSWorld
[OSWorld](benchmarks/osworld.md) is a scalable, real computer environment for multimodal agents that supports task setup, execution-based evaluation, and interactive learning across operating systems. Key features include:

- Supports multiple operating systems (Ubuntu, Windows, macOS)
- Includes 369 real-world computer tasks with reliable setup and evaluation scripts
- Enables cross-app workflows and arbitrary application interactions
- Provides execution-based evaluation functions
- Supports parallel environment execution

## Benchmark Results

## Benchmark Results Summary

Latest benchmark results across major evaluation frameworks as of April 2024. Human performance on OSWorld: >72.36%.

| Model | WebArena | OSWorld | Openness | Notes |
|-------|----------|---------|----------|--------|
| [OpenAI Operator](closed/openai-operator.md) | 58.0% | 38.0% | Closed | Best overall on both benchmarks |
| [Jace.AI](closed/jace-ai.md) | 57.1% | N/A | Closed | Action description + Screenshots |
| [ScribeAgent](closed/scribeagent.md) | 53.0% | N/A | Closed | Proprietary training data |
| [ORCHESTRA](closed/orchestra.md) | 52.1% | N/A | Closed | By UNC x Ventus |
| [Learn-by-Interact](open/learn-by-interact.md) | 48.0% | N/A | Open | Best open source on WebArena |
| [AgentOccam-Judge](open/agentoccam-judge.md) | 45.7% | N/A | Open | |
| [UI-TARS-72B-DPO](open/ui-tars.md) | N/A | 24.6% | Open | Best on OSWorld |
| [OSCAR](open/oscar.md) | N/A | 24.5% | Open | Best screenshot-based model |
| [Aguvis-72B](open/aguvis.md) | N/A | 17.04% | Open | Multimodal approach |
| [Aria-UI](closed/aria-ui.md) | N/A | 15.15% | Closed | By HKU & Rhymes AI |
| [OS-Atlas](open/os-atlas.md) | N/A | 14.63% | Open | Multiple model sizes |
| [SeeClick](open/seeclick.md) | N/A | 9.21% | Open | Visual interaction focus |

For detailed results and analysis, see the individual benchmark pages:
- [WebArena Benchmark](benchmarks/webarena.md)
- [OSWorld Benchmark](benchmarks/osworld.md)

### References
[1] WebArena: A Realistic Web Environment for Building Autonomous Agents (https://arxiv.org/pdf/2307.13854)
[2] OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments (https://arxiv.org/abs/2404.07972)

## Current Solutions

### Closed Source Solutions
* [Anthropic Computer Use](closed/anthropic-computer-use.md): Claude AI's computer use capability
* [Gumloop](closed/gumloop.md): AI-powered automation platform with visual workflow builder
* [Lutra](closed/lutra.md): AI-driven workflow automation platform
* [OpenAI Operator](closed/openai-operator.md): Upcoming autonomous AI agent for computer tasks
* [Zapier](closed/zapier.md): No-code automation platform connecting various apps and services

### Open Source Solutions
* [n8n](open/n8n.md): Workflow automation platform with extensive integration options
* [OpenAdapt](open/openadapt.md): Generative process automation framework
* [OpenHands](open/openhands.md): AI-powered software development platform


