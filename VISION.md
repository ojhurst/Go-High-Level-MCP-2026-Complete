# Go-High-Level MCP 2026 Complete — Vision

## What This Is
Third-party open-source MCP server providing access to the entire GoHighLevel API — 563+ tools covering every sub-account-level endpoint. This is a reference library, not something we run in production.

## The Problem
Building GHL API integrations from scratch means reading docs, handling auth, managing rate limits, and writing boilerplate for every endpoint. This project wraps all of that into MCP tools that any AI can call directly.

## What It Does Today
- 563+ MCP tools covering contacts, conversations, calendars, opportunities, invoices, payments, workflows, Voice AI, social media, blogs, forms, funnels, and more
- TypeScript with full type definitions
- Rate limiting and auth handling built in
- Deployable to Vercel, Railway, or Docker

## Where It's Going (For Us)
We use this as a reference library — when we need to add a new GHL tool to our own `gokartpark-mcp` server, we check here first for implementation patterns instead of starting from scratch. We don't run it directly because we only need a subset of tools and want tighter control over what's exposed.

The GHL API cookbook we consult but don't serve.
