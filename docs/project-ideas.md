# Portfolio Project Ideas (SDET focus)

Below are five projects that show architecture thinking, reliability, and
CI-first automation. Each can be a standalone repo under projects/.

---

## 1) E2E Automation Framework (Playwright + TypeScript)

Concept
- Build a production-quality Playwright framework with POM, fixtures,
  deterministic selectors, and CI support.

Tech stack
- Playwright Test, TypeScript, Node.js, GitHub Actions, Allure or HTML report

What problems it demonstrates
- Reliable E2E testing at scale
- Parallel-safe design and data handling
- Clear separation of test intent vs UI mechanics

README outline
- Problem and scope
- Architecture (POM, fixtures, utils)
- Reliability strategies
- How to run locally and in CI
- Reports and artifacts

Key features
- Fixtures for auth, test data, and cleanup
- Centralized selector strategy (data-testid)
- Soft vs hard assertions used intentionally
- Flaky-test mitigation and retries policy

Skills it signals
- E2E architecture, Playwright expertise, CI integration
- Test reliability and maintainability focus

---

## 2) API Testing Framework (REST + Schema + Contract)

Concept
- A robust API testing toolkit with schema validation and contract checks.

Tech stack
- Playwright API testing or Supertest, TypeScript, Zod or AJV, GitHub Actions

What problems it demonstrates
- Preventing breaking changes via contract tests
- Validating responses beyond status codes
- Reusable API test helpers and data builders

README outline
- API coverage strategy
- Schema and contract validation
- Environments and data setup
- CI workflow and reporting

Key features
- Strong assertions with schema validation
- Request/response logging on failures
- Environment-agnostic base URLs and secrets handling

Skills it signals
- API test design, contract testing, reliability focus

---

## 3) CI/CD Quality Gates (GitHub Actions)

Concept
- A CI pipeline that runs tests in parallel, generates reports, and enforces
  quality gates.

Tech stack
- GitHub Actions, Playwright/Cypress, Node.js, report tooling

What problems it demonstrates
- CI stability and reproducibility
- Automated feedback loops for releases

README outline
- CI goals and quality gates
- Workflow design (matrix, caching, artifacts)
- How to read reports and logs

Key features
- Browser matrix and shard support
- Artifacts for traces, videos, screenshots
- Failure triage checklist

Skills it signals
- CI/CD ownership, pipeline design, operational thinking

---

## 4) Test Architecture Demo (Pyramid + Data Strategy)

Concept
- A demo repo that shows test pyramid discipline with a focus on
  data strategy and environment control.

Tech stack
- Playwright (UI), API client, TypeScript, Docker (optional)

What problems it demonstrates
- Choosing the right test type for the risk
- Avoiding flaky tests with controlled data setup

README outline
- Test pyramid and scope
- Data setup and teardown strategy
- Parallel safety and environment config

Key features
- Data seeding utilities or API-based setup
- Clear Arrange/Act/Assert examples
- Risk-based test coverage map

Skills it signals
- Architecture thinking, reliability strategy, leadership mindset

---

## 5) Performance and Security Smoke Checks

Concept
- Lightweight performance checks and security baseline scanning in CI.

Tech stack
- k6 (performance), OWASP ZAP (security), GitHub Actions

What problems it demonstrates
- Guardrails for regressions early in the pipeline
- Understanding of non-functional testing

README outline
- What is measured and why
- How to run locally and in CI
- Thresholds and failure criteria

Key features
- Simple k6 thresholds and trend outputs
- ZAP baseline scan with report artifacts
- Clear pass/fail criteria

Skills it signals
- Broader QA perspective, CI integration, risk-based thinking
