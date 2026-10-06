# Luis Gonzalez

**Software engineer. 4+ years of C# and .NET.**

I build backend services and the web apps on top of them, mostly ASP.NET Core with PostgreSQL behind a React or Next.js frontend. I like owning the whole path to production: tests in CI, signed releases, and dashboards that show when something breaks. I work as a Programmer Analyst at Columbia Machine in Vancouver, WA, building internal .NET applications and AI tooling.

## Transcendence

League of Legends analytics. **[Live site](https://transcend.kronic.one)** · **[Source](https://github.com/luisgon-dev/Transcendence)**

A .NET 10 worker crawls Riot's ranked ladders on 10 platforms and ingests matches into PostgreSQL. Hangfire jobs precompute tier lists, builds, and matchups, an ASP.NET Core API serves the results, and a Next.js 16 frontend renders them.

As of October 2026:

- **560K+ matches** in a 300 GB PostgreSQL database, with about **23K new matches a day**
- **CI on every PR:** xUnit, Testcontainers integration tests, an OpenAPI drift check, and k6 and Lighthouse performance budgets
- **Deploys:** cosign-signed images and a pull-based deploy that verifies signatures, migrates first, and rolls back on failed health checks
- **Observability:** OpenTelemetry metrics, 9 Grafana dashboards, and 18 alerts

## Tech

- **Languages:** C#, TypeScript, Python, Rust
- **Backend:** .NET, ASP.NET Core, EF Core, Hangfire
- **Data:** PostgreSQL, Redis
- **Frontend:** React, Next.js
- **Delivery and ops:** Docker, GitHub Actions, OpenTelemetry, Prometheus, Grafana

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/luisgon-dev/luisgon-dev/output/pacman-contribution-graph-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/luisgon-dev/luisgon-dev/output/pacman-contribution-graph.svg">
    <img alt="Pac-Man contribution graph" src="https://raw.githubusercontent.com/luisgon-dev/luisgon-dev/output/pacman-contribution-graph.svg" />
  </picture>
</p>
