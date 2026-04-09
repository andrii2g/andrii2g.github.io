# Repository Naming Guidelines

## Rules

- lowercase only
- kebab-case (hyphens)
- no spaces
- no special characters
- 3–5 words max

## Structure

[prefix]-[domain]-[purpose]

---

## Prefix (REQUIRED)

| Prefix   | Meaning |
|----------|--------|
| tool     | utility or script |
| dotnet   | C# / .NET |
| cpp      | C++ |
| iot      | hardware / Arduino / Raspberry PI / SMT /etc |
| print    | 3D printing |
| infra    | infrastructure |
| lab      | experiments |

---

## Domain (optional but recommended)

telegram, aws, kafka, vrf, web, api, printer, sensor

---

## Examples

Good:
- tool-telegram-parser
- dotnet-vrf-orchestrator
- iot-greenhouse-monitor

Bad:
- MyProject
- test123
- cool-stuff

---

## Forbidden

- camelCase
- underscores
- version suffixes (v2, final)
- vague names (app, service, tool)