# Priority Pass + Taxi App Integration

## Architecture Overview
- RESTful APIs for flight info, taxi booking, and lounge access
- Rationale: Modular, scalable, and easy to integrate with external providers

## PCI Compliance
- All payment data handled via Stripe (PCI DSS Level 1)
- No card data stored on our servers
- HTTPS enforced across all endpoints

## Omissions & Trade-offs
- Skipped real-time taxi tracking for MVP
- Used mock data for lounge availability
- UI polish deferred to focus on backend integration

## Shortcuts Taken
- Hardcoded flight data for demo purposes
- No automated tests yet (manual testing only)
- Will add CI/CD and monitoring in next sprint
