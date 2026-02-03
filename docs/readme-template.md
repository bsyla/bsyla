# Project README Template (QA/SDET)

Use this template for every portfolio project to keep it consistent and
recruiter-friendly. Replace all placeholders.

---

# <Project Name>

One-line summary of what this project demonstrates.

## Why this exists
- The problem it solves
- The risk or quality gap it addresses
- Why this approach is reliable and scalable

## Tech stack
- Language:
- Frameworks:
- CI:
- Reporting:

## Architecture
- High-level diagram (link to diagrams/README.md or image)
- Key design decisions and tradeoffs

## Test scope
- In scope:
- Out of scope:

## Reliability strategies
- Deterministic selectors (data-testid)
- No arbitrary waits (use expect.poll or proper async waits)
- Parallel-safe data setup and cleanup

## How to run
### Local
1. <setup>
2. <install>
3. <run>

### CI
- GitHub Actions workflow: <link or path>

## Key features
- Feature 1
- Feature 2
- Feature 3

## Example test (short)
```ts
// Short example that shows Arrange / Act / Assert
```

## Reporting
- Where reports are generated
- How to read results

## Folder structure
```
<tree>
```

## Limitations and next steps
- Known limitations
- Planned improvements
