# Eachlabs API Specifications

This repository contains the **official OpenAPI specifications** for public and partner-facing APIs exposed by **Eachlabs.ai**.

These specifications are the single source of truth used to:
- Render API documentation (via Scalar)
- Align internal teams and external integrators
- Provide stable, versioned contracts for our platform APIs

If you are integrating with Eachlabs, this is where you should start.

---

## About Eachlabs.ai

**Eachlabs.ai** is a unified AI workflow platform that allows teams and developers to run, orchestrate, and scale AI models across multiple providers through a single, consistent API.

We focus on:
- Provider-agnostic AI execution
- Workflow orchestration and automation
- Predictable pricing and usage tracking
- Production-ready integrations (not demos)

Our platform abstracts the operational complexity of working with multiple AI vendors while giving developers fine-grained control over inputs, outputs, and execution logic.

---

## API Entry Points

High-level entry points for the Eachlabs platform:

- **Base API URL**  
  `https://api.eachlabs.ai/v1/docs`

- **Authentication**  
  API key–based authentication via `X-API-Key: <token>`

Detailed auth flows and examples are described in the individual OpenAPI specs.

---

## Versioning & Stability

- Breaking changes are released under **new API versions**
- Non-breaking changes may be added within an existing version
- Deprecated fields and endpoints are explicitly marked in the specs

Do not rely on undocumented behavior.

---

## Feedback & Issues

If you find:
- inconsistencies in the specs
- unclear request/response definitions
- missing examples

Please open an issue in this repository.  
For commercial or partnership inquiries, contact us directly.

---

## Useful Links

- Website: [https://eachlabs.ai](https://eachlabs.ai ) 
- Twitter / X: [https://x.com/eachlabs](https://x.com/eachlabs)
- LinkedIn: [https://www.linkedin.com/company/eachlabs/](https://www.linkedin.com/company/eachlabs/)

---

© Eachlabs.ai
