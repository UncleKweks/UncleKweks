## Kwesili Okafor

Backend engineer working on systems that move money. Go, PostgreSQL and gRPC, with a security background from smart contract auditing.

I care about the parts of a backend where a wrong state costs real money: balances that always reconcile, retries that never charge twice, and permission checks that hold under abuse.

### Projects

- **[ledger-service](https://github.com/UncleKweks/ledger-service)**: double-entry ledger in Go and PostgreSQL, served over REST and gRPC from one service layer. PostgreSQL enforces the invariants itself: entries sum to zero (deferred constraint trigger), history is append-only, per-account row locks stop overdrafts under concurrency, and idempotency keys make retries safe. Tested against real Postgres with race-detector runs in CI.
- **[ticket-api](https://github.com/UncleKweks/ticket-api)** + **[booking-app](https://github.com/UncleKweks/booking-app)**: REST API in pure Go (no framework, no ORM) with a booking frontend and a goroutine-based async notifier.
- **[go-hackernews-clone](https://github.com/UncleKweks/go-hackernews-clone)**: link aggregator on `net/http`, `html/template` and SQLite, with sessions, bcrypt auth, voting, comments and pagination.

### Production work

- **G-Nation (Backshire Platinum)**: took a five-contract payment platform from client brief to production on Base mainnet. TypeScript and Solidity, 26/26 passing end-to-end suite before release.
- **Ackee Blockchain**: security review of production smart contracts.

### Security

Competitive auditor on Sherlock, CodeHawks and Code4rena.

| Contest | Platform | Result |
|---|---|---|
| Crestal Network | Sherlock | 1 High, solo |
| Eggstravaganza | CodeHawks First Flight | 1st place (3 H, 3 M, 3 L) |
| RustFund | CodeHawks First Flight | 10th (3 H, 2 M) |
| Storage Proofs | CodeHawks | 9th |
| RAAC Core Contracts | CodeHawks | 1 H, 2 M |

### Stack

Go · PostgreSQL · gRPC · REST · Docker · TypeScript/Node.js · Rust · Solidity · Python

### Contact

[LinkedIn](https://www.linkedin.com/in/chimkwesili-okafor-a80562384) · kwesiliokafor25@gmail.com

Open to backend engineering roles: relocation (EU/UK) or remote.
