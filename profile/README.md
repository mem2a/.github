<p align="center">
  <a href="https://mem2a.github.io/mem2a/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://mem2a.github.io/mem2a/assets/brand/mem2a-logo-dark.svg">
      <img src="https://mem2a.github.io/mem2a/assets/brand/mem2a-logo.svg" alt="Mem2A" height="64">
    </picture>
  </a>
</p>

<p align="center">
  <strong>An open protocol, built on A2A, that lets any AI agent consult a company's shared memory before it acts, hear when that changes, and report back after.</strong>
</p>

<p align="center">
  <a href="https://mem2a.github.io/mem2a/">Documentation</a> ·
  <a href="https://mem2a.github.io/mem2a/specification/">Specification</a> ·
  <a href="https://github.com/mem2a/mem2a">Repository</a> ·
  <a href="https://mem2a.github.io/mem2a/community/">Take part</a>
</p>

Companies are filling up with AI agents from many vendors, and none of them shares a view of what the company has decided. Mem2A gives every agent, whoever built it, one company-owned memory to check with. Before an agent acts, memory tells it the facts, precedent and rules that bear on the action. While the agent works, memory tells it what changed. After, the agent reports what it did.

## Start here

| If you want to | Go to |
| --- | --- |
| Understand the problem | [Why Mem2A](https://mem2a.github.io/mem2a/why/) and [how it works](https://mem2a.github.io/mem2a/how-it-works/) |
| See it run | The [Acme demo](https://mem2a.github.io/mem2a/guides/acme-demo/): two agents and a memory, in one command |
| Connect an agent | [Start here](https://mem2a.github.io/mem2a/start-here/), then the [Python SDK](https://mem2a.github.io/mem2a/guides/python/), or plain HTTP with the [wire quickstart](https://mem2a.github.io/mem2a/wire-quickstart/) |
| Build a memory | The [specification](https://mem2a.github.io/mem2a/specification/) and the [implementer's guide](https://mem2a.github.io/mem2a/implementers-guide/), then test it with `mem2a-conform` |
| Enforce memory on tool calls | The [tool gateway example](https://mem2a.github.io/mem2a/guides/tool-gateway/) |
| Find where you fit | [Who Mem2A is for](https://mem2a.github.io/mem2a/ecosystem/) |

## Repositories

| Repository | What's in it |
| --- | --- |
| [mem2a/mem2a](https://github.com/mem2a/mem2a) | The specification, its JSON Schemas and worked examples; a Python reference implementation, SDK and conformance checker; runnable examples; and the documentation |

SDKs for more languages are on the [roadmap](https://mem2a.github.io/mem2a/roadmap/), and [implementations by anyone](https://mem2a.github.io/mem2a/community/implementations/) are welcome.

## Status

Mem2A 0.1 is a **draft for review**: expect breaking changes before 1.0. It's an extension of [A2A](https://a2a-protocol.org/) v1.0, and we intend to propose it to the A2A project. The design questions still open are [tracked as issues](https://github.com/mem2a/mem2a/issues?q=is%3Aissue+is%3Aopen+label%3A%22open+question%22), and evidence from real deployments is the most useful thing you can bring to them.

## Take part

- **Ask a question or share a use case** in [issues](https://github.com/mem2a/mem2a/issues/new/choose).
- **Become a design partner** if you run agents from more than one vendor: [tell us about them](https://github.com/mem2a/mem2a/issues/new?template=design-partner.yml).
- **Help maintain Mem2A.** We're looking for [co-maintainers from other companies](https://github.com/mem2a/mem2a/issues/19).
- **Talk to us privately** through [Sentra's contact page](https://www.sentra.app/contact). Report security problems as the [security policy](https://github.com/mem2a/mem2a/security/policy) describes.

<sub>Mem2A was started by <a href="https://sentra.app">Sentra</a>. It's an open specification under the Apache License 2.0, developed in the open under a documented <a href="https://github.com/mem2a/mem2a/blob/main/GOVERNANCE.md">governance process</a> and <a href="https://github.com/mem2a/mem2a/blob/main/CODE_OF_CONDUCT.md">code of conduct</a>.</sub>
