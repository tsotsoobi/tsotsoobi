# Adokwei Andrew Addo

Researcher in health financing. I build agent infrastructure, market observers, and peer-to-peer logistics, mostly in TypeScript and Rust, from Accra.

## Building

**[gyema-app](https://github.com/tsotsoobi/gyema-app)** and **[gyema-app-mainnet](https://github.com/tsotsoobi/gyema-app-mainnet)**  
Peer-to-peer parcel delivery on Pi Network. Next.js, Supabase auth bridged on `pi_username`, in-memory sessions. The consumer surface and its production deployment.

**[gyema-contracts](https://github.com/tsotsoobi/gyema-contracts)**  
Soroban contracts for V2 escrow: three-pot model, customer-confirms-primary release, admin-arbitrated dispute resolution. 762 lines of Rust, 12 passing tests, CI green across five jobs.

**[multi-pulse](https://github.com/tsotsoobi/multi-pulse)**  
A read-only AMM observer across Stellar and XRPL mainnet. Walks live pools, prices a size ladder against exact constant-product maths, records what would have cleared a net threshold. It never signs or submits, and the test suite enforces that at source level rather than asserting it in prose. [FINDINGS.md](https://github.com/tsotsoobi/multi-pulse/blob/main/FINDINGS.md) reports a 28-hour run across roughly 39,000 pools, including five measurement defects found by running the thing rather than reading it.

**health-agent-mesh** (private)  
A monorepo of clinical AI agents with safety boundaries enforced in CI rather than documented in a policy: no diagnosis, no prescription, no service-role key, a single egress function that pseudonymises clinical fields before anything leaves. Architecture decision records cover data residency and governance.

**[pillgh.com](https://github.com/tsotsoobi/pillgh.com)**  
Pi Logistics Ltd., the freight forwarding company behind Gyema.

## Gyema

The core infrastructure is complete and proven end to end on both rails: matching, delivery attestation with courier presence proof, and a tested on-chain escrow awaiting Pi's Mainnet contract access. What remains is the network itself, which is a distribution problem rather than an engineering one: enough density on Accra's routes to make a match likely, then the corridors out from there.

The bet behind it: decentralised peer-to-peer logistics is the right primitive for African last-mile delivery. Existing travel routes already carry packages. Senders pay travellers directly, settlement happens on-chain, and contracts handle escrow and disputes. No central depot, no fleet capex, no intermediary sorting centres.

## Research

Presented at ICAIH 2026, University of Health and Allied Sciences, Ho, on autonomous AI agents in health system reform.

## How I work

Boundaries enforced by tests rather than stated in comments. Architecture decisions recorded when they are made, not reconstructed afterwards. Measurement instruments audited before their output is believed, which is most of what FINDINGS.md is about. Floors and thresholds chosen before collection starts, not tuned mid-run.

Most of what I build runs against live financial or clinical systems, so the interesting work is usually in what a system refuses to do.

## Elsewhere

Accra, Ghana. Shipping in public.

[pillgh.com](https://pillgh.com) · [@pillghana](https://x.com/pillghana)
