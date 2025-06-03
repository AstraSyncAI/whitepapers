# Current Solutions: Building Blocks for a Complete Architecture

The technology industry has responded to the attribution crisis with characteristic innovation. Multiple solutions have emerged, each addressing specific aspects of the challenge. Rather than dismissing these as insufficient, let us understand their contributions and limitations.

## Agent ID via Traditional Enterprise-Grade Identity

Extending traditional human user identity solutions to cover AI agents represents a natural evolution of enterprise identity management. Its strengths are substantial:

**Capabilities:**

* Unified identity across relevant platforms
* Role-based access control with granular permissions
* Integration with existing Active Directory infrastructure
* Audit logging within server compliance framework

**Optimal Use Cases:**

* Enterprises already invested in vendor infrastructure
* Internal AI agents operating within defined boundaries
* Scenarios requiring tight integration with integrated solutions

**Limitations:**

* Platform-specific implementation limits interoperability
* Mutable database architecture allows potential tampering
* No cross-platform standards for agent interaction
* Pricing model may exclude smaller organisations

For organisations living within the relevant ecosystem, this solution provides genuine value. The limitation is not capability, it is scope.

## Biometric-Bound Agent Identity

Another approach is effectively binding an agent to a biometrically authenticated humans:

**Technical Implementation:**

* Decentralised biometric cloud supporting face, voice, finger, iris, and palm
* Identity token management for agent authorisation
* Traditional database architecture with distributed storage

**Strengths:**

* Leverages proven biometric authentication technology
* Strong privacy protections through decentralised storage
* Immediate applicability for human-initiated agent actions
* Partnership demonstrates real-world deployment

**Critical Limitations:**

* Biometric-only approach fails to address agent-to-agent interactions
* Traditional database architecture remains vulnerable to tampering
* No immutable audit trail for compliance verification
* Retrofitting existing technology rather than purpose-built solution
* Limited to authentication without broader governance capabilities

Market entry with this solution validates market demand but illustrates the limitations of adapting existing identity solutions to the unique challenges of AI agent governance. The focus on biometric binding addresses only one aspect of the attribution challenge outlined by Chan et al. (2025).

## The Protocol Ecosystem: Essential Communication Layers

Three major protocols have emerged to enable agent communication:

**Model Context Protocol (MCP) - Anthropic's November 2024 release**

* Standardises model-to-tool communication
* Reduces integration complexity for developers
* Provides consistent context handling
* Well-documented with reference implementations

**Agent Communication Protocol (ACP) - IBM's January 2025 extension**

* Builds on MCP for agent-to-agent interaction
* Adds transaction semantics and state management
* Includes basic trust establishment mechanisms
* Open-source with active community development

**Agent-to-Agent (A2A) - Google's April 2025 standard**

* Focus on seamless multi-agent orchestration
* Advanced routing and discovery mechanisms
* Performance optimised for high-frequency interaction
* Adopted by Microsoft in May 2025, signaling industry convergence

These protocols solve real problems. They are not competitors to governance infrastructure, they are complementary layers that governance must support.

## The Integration Challenge

Each solution excels within its domain but struggles at boundaries:

* Entra agents cannot meaningfully interact with Google Workspace agents
* Protocols enable communication but not accountability
* Biometric solutions address human-agent but not agent-agent trust
* No universal identity standard exists across platforms
* Compliance requirements vary by jurisdiction with no unifying framework

This is not failure, it is the natural evolution of a rapidly developing ecosystem. What is missing is the governance layer that enables these components to work together trustfully.
