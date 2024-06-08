# AIDomesticate (AID)

**AIDomesticate (AID)** is a modular and extensible framework designed to simplify the creation and management of AI agents using LangChain and the OpenAI GPT-4 API. The framework is built to support various maturity phases of AI agent development, ensuring a gradual and controlled transition from human-in-the-loop systems to fully autonomous operations.

## Features

- **Modular Design**: Easily create, extend, and integrate different AI agents, including Planners, Makers, and Supervisors.
- **Maturity Phases**: Implement systems with distinct phases of maturity:
  - **Phase 1**: Human debugging for refining agent interactions.
  - **Phase 2**: Supervisor-led iteration with human approval for critical steps.
  - **Phase 3**: Full autonomy with minimal human intervention.
- **Specialist Supervisors**: Utilize specialized supervisors for planning and execution tasks, enhanced by the Retrieval-Augmented Generation (RAG) approach for better context and accuracy.
- **Open Source**: Licensed under the MIT License, encouraging collaborative development and contribution from the community.

## Getting Started

- [Getting Started](getting_started.md)
- [API Reference](api_reference.md)
- [Contributing](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
