# GenUI Plan

This document provides an overview of the Generative UI architecture implementation for the Copilot Space workspace.

## Quick Links

- [Full GenUI Plan Documentation](content/4.generative-ui/1.GenUI_Plan.md)
- [CopilotKit Integration](content/4.generative-ui/2.Generative%20UI%20Plan%20with%20CopilotKit.md)
- [Implementation Guide](content/4.generative-ui/3.Implementing%20Generative%20UI%20Architecture.md)

## Overview

The Generative UI architecture supports three primary archetypes:

### 1. Static (Registry-based)
- Pre-defined, reusable UI components with known interfaces
- Type-safe interfaces with predefined props
- Ideal for common UI patterns and layouts

### 2. Declarative (Schema-driven)
- Dynamic UI generation from structured schemas
- JSON/YAML schema definitions
- Configuration-over-code approach

### 3. Open-Ended (Sandbox)
- AI-generated UI with maximum flexibility
- Sandboxed execution environment
- Security constraints and validation

## Core Technologies

- **Next.js**: React framework for server-side rendering and routing
- **CopilotKit**: AI integration framework for building copilot experiences
- **Material-UI (MUI)**: Component library for consistent, accessible UI
- **Sandboxed HTML**: Secure execution environment for dynamic content

## Architecture Components

### Component Registry
Central repository for all registered UI components with validation and type checking.

### Schema Validator
Ensures schema compliance and type safety for declarative UI generation.

### Sandbox Manager
Manages secure execution of AI-generated code with resource limits and security policies.

## Getting Started

1. Review the [full GenUI plan](content/4.generative-ui/1.GenUI_Plan.md)
2. Understand [CopilotKit integration](content/4.generative-ui/2.Generative%20UI%20Plan%20with%20CopilotKit.md)
3. Follow the [implementation guide](content/4.generative-ui/3.Implementing%20Generative%20UI%20Architecture.md)
4. Set up the [development environment](.devcontainer/generative-ui/devcontainer.json)

## Development Environment

A pre-configured development container is available at `.devcontainer/generative-ui/devcontainer.json` with all necessary tools and extensions for Generative UI development.

## Documentation

For detailed documentation, see the comprehensive guides in the `content/4.generative-ui/` directory:

- **GenUI_Plan.md**: Complete architectural overview
- **Generative UI Plan with CopilotKit.md**: CopilotKit integration details
- **Implementing Generative UI Architecture.md**: Step-by-step implementation guide

## References

- [CopilotKit Documentation](https://docs.copilotkit.ai/)
- [Next.js Documentation](https://nextjs.org/docs)
- [MUI Documentation](https://mui.com/)
- [Repository](https://github.com/Ditto190/ag2)
