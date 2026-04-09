# Tags Guidelines

## Rules

- lowercase only
- use predefined vocabulary where possible
- 3 to 7 tags per repository is recommended
- tags must be relevant and useful for filtering
- avoid duplicates and synonyms
- use hyphenated tags when needed

---

## Required Composition

Each repository should include:

- at least 1 tech tag
- at least 1 domain tag
- at least 1 type tag

Recommended structure:

- 1–2 tech tags
- 1–3 domain tags
- 1–2 type tags
- optional extra tags for architecture, runtime, or platform

---

## Allowed Tag Groups

### Tech Tags

- dotnet
- csharp
- cpp
- c
- python
- bash
- powershell
- javascript
- typescript
- html
- css
- blazor
- minimal-api
- aspnet
- php
- java
- kotlin
- go
- rust
- sql

### Framework / Platform Tags

- telegram
- github
- aws
- docker
- nginx
- linux
- windows
- arduino
- esp32
- raspberry-pi
- mysql
- redis
- kafka
- signalr
- opentelemetry

### Domain Tags

- api
- web
- backend
- frontend
- cli
- automation
- parser
- converter
- exporter
- importer
- scraper
- monitoring
- orchestration
- simulation
- vr-forces
- mak-rti
- sticker-pack
- chatbot
- bot
- home-automation
- greenhouse
- sensor
- dashboard
- infrastructure
- devops
- ci-cd
- testing
- security
- networking
- 3d-printing
- slicer
- firmware
- electronics
- embedded
- robotics
- productivity
- templates
- reference

### Type Tags

- tool
- utility
- script
- service
- library
- sdk
- app
- prototype
- experiment
- template
- starter
- example

### Status / Maturity Tags

Use sparingly if needed:

- active
- experimental
- archived

---

## Tag Selection Guidance

### Prefer canonical tags

Use:

- dotnet
- cpp
- cli
- tool

Avoid:

- c#
- c-plus-plus
- command-line
- tools

---

## Recommended Tag Count

- minimum: 3
- preferred: 4 to 6
- maximum: 8

---

## Examples

### Example 1

Repository: `tool-telegram-sticker-viewer`

```yaml
tags:
  - dotnet
  - telegram
  - sticker-pack
  - web
  - tool
```

### Example 2

Repository: `dotnet-vrf-orchestrator`

```yaml
tags:
  - dotnet
  - mak-rti
  - vr-forces
  - orchestration
  - service
```

### Example 3

Repository: `iot-greenhouse-monitor`

```yaml
tags:
  - python
  - esp32
  - greenhouse
  - sensor
  - monitoring
  - prototype
```

### Example 4

Repository: `bash-github-pages-helper`

```yaml
tags:
  - bash
  - github
  - automation
  - cli
  - script
```

---

## Forbidden

- uppercase tags
- random one-off tags with no reuse value
- vague tags with no filtering value
- duplicate-meaning tags in the same repo

Bad examples:

- cool
- project
- my-stuff
- c#
- Cpp
- tools

---

## Tag Priority

When choosing tags, prioritize:

1. implementation technology
2. primary domain
3. repository type
4. notable platform or runtime
5. special function if important

---

## Tagging Strategy

Use tags for details.  
Use categories for broad grouping.

Example:

Category:

- Telegram

Tags:

- dotnet
- telegram
- bot
- api
- tool
