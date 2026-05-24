## Adokwei Addo

Adokwei is building [Gyema](https://github.com/tsotsoobi/gyema-app) — peer-to-peer delivery on Pi Network, built in Ghana for the world.

Gyema connects two sides of every delivery: **Senders** with packages to move and **Travellers** already making the trip. Pi is the payment rail. The platform is live on Pi Testnet — 4.8★ on Pi App Studio. V2 on-chain escrow contracts are ready (Soroban / Rust), pending Pi Mainnet Soroban access for third-party apps.

---

### Building

- **[gyema-app](https://github.com/tsotsoobi/gyema-app)** — Next.js frontend, Supabase auth bridge keyed on `pi_username`, in-memory sessions. The main consumer surface.
- **[gyema-contracts](https://github.com/tsotsoobi/gyema-contracts)** — Soroban smart contracts for V2 escrow: three-pot model, customer-confirms-primary release, admin-arbitrated dispute resolution. 762 lines of Rust, 12 passing tests.
- **[gyema-backend](https://github.com/tsotsoobi/gyema-backend)** — supporting infrastructure.
- **[pillgh.com](https://github.com/tsotsoobi/pillgh.com)** — Pi Logistics Ltd. — the company behind Gyema.

---

### Bet

Decentralized peer-to-peer logistics is the right primitive for African last-mile delivery. Existing travel routes carry packages; senders pay travellers directly; Pi handles settlement; smart contracts handle escrow and disputes. No central depot, no fleet capex, no intermediary sorting centers.

Pi Network is the right rail because it brings KYC-verified identity and a payment layer to a population that hasn't been served well by either banking infrastructure or earlier crypto attempts. Pi Testnet is already on Protocol 23 with Soroban-style smart contract foundations; Mainnet follows.

---

### Based in

Accra, Ghana — shipping in public.

[Twitter / X (@pillghana)](https://www.twitter.com/pillghana) · [Pi Logistics Ltd.](https://pillgh.com)
