# QueryLift

QueryLift is a Shopify application built to improve merchant product workflows and provide reliable tooling around Shopify catalog data.

The project uses TypeScript, React Router, Shopify Polaris and Shopify's GraphQL Admin API, with an emphasis on maintainability, testing and reliable API interactions.

> Production source code is maintained in a private repository.

## Tech Stack

- TypeScript
- React Router
- Shopify Polaris
- Shopify GraphQL Admin API
- Node.js
- Prisma
- Automated testing
- Git / GitHub

## Engineering Highlights

- Built Shopify application interfaces and workflows using TypeScript and React Router.
- Integrated Shopify's GraphQL Admin API for product and store data.
- Centralized GraphQL interactions to improve consistency and error handling across the application.
- Hardened API workflows against malformed responses and GraphQL-level failures.
- Added bounded catalog processing to avoid unsafe assumptions when working with larger stores.
- Implemented application states for partial catalog analysis when the complete catalog could not safely be processed.
- Debugged frontend, API and data-flow issues across a multi-file application codebase.
- Built automated regression coverage around important application behavior.

## Reliability & Testing

A major focus of QueryLift has been making integrations predictable and testable rather than relying only on happy-path behavior.

The project currently passes:

- **129 automated tests**
- TypeScript type checking
- Production build validation
- Real Shopify development-store smoke testing

GraphQL access was also consolidated so application code uses a shared reliability layer instead of making inconsistent API calls throughout the codebase.

## Shopify Integration

QueryLift works with Shopify merchant data through the Admin GraphQL API.

Development has included:

- Product catalog retrieval
- GraphQL query handling
- API error handling
- Catalog-size safeguards
- Webhook-related workflows
- Application billing logic
- Store lifecycle handling

## Engineering Approach

The project has been developed using incremental reliability improvements:

1. Inspect existing behavior before changes
2. Add automated regression coverage
3. Centralize important external API interactions
4. Handle API and data edge cases explicitly
5. Validate with type checking and tests
6. Create production builds
7. Smoke test against a real Shopify development store

## Source Code

The primary application repository is private because it contains active application and integration code.

This public repository documents the architecture, technologies and engineering work completed on the project.

## Developer

**Risto Caissie**  
Software Developer — Calgary, Alberta

📧 ristocaissie1@gmail.com
