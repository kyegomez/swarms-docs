# Swarms Docs

Welcome to Swarms Docs!

This documentation covers the fundamentals of the **Swarms** framework and describes how to use **Swarms Tools**.

## Swarms

The Swarms framework provides developers with the ability to create AI systems that operate across two dimensions: predictability and creativity. For predictability, Swarms enforces structures like sequential pipelines, DAG-based workflows, and long-term memory. To facilitate creativity, Swarms safely prompts LLMs with [tools](https://github.com/swarms-ai/swarms-tools) and short-term memory connecting them to external APIs and data stores. The framework allows developers to transition between those two dimensions effortlessly based on their use case.

Swarms not only helps developers harness the potential of LLMs but also enforces trust boundaries, schema validation, and tool activity-level permissions. By doing so, Swarms maximizes LLMs’ reasoning while adhering to strict policies regarding their capabilities.

[Learn more about swarms →](swarms-framework/)

## Swarms Tools

**swarms-tools** is a PyPI package with official tools. It's a great way to start using Swarms to see how easy it can be to build applications that extend LLMs' creative capabilities. Agents (or any other structure for that matter) can be used to connect your pre-processed data to LLMs via tools. Swarms tools are Python classes with activities. Activities are Python methods decorated with the @activity decorator. Each activity has a description (used to provide context to the LLM) and the input schema that the LLM must follow in order to use the tool. Swarms validates LLM outputs against the schema to ensure each tool activity is used correctly.

[Learn more about swarms tools →](swarms-tools/)

## Examples

Check out Swarms examples for building agents, data retrieval, and more.

[Checkout Swarms examples →](examples/)
