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
|----------|---------|
| tool     | utility or helper tool |
| script   | small script-based repo |
| dotnet   | C# / .NET project |
| cpp      | C++ project |
| python   | Python project |
| web      | website or frontend project |
| api      | API/backend-focused project |
| infra    | infrastructure / hosting / deployment |
| devops   | CI/CD, automation, operational tooling |
| iot      | hardware / Arduino / Raspberry PI / ESP32 |
| embedded | embedded systems project |
| print    | 3D printing |
| home     | household or home automation |
| lab      | experiments / prototypes |
| data     | parsing, conversion, extraction, analytics |
| docs     | documentation / templates / reference |

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