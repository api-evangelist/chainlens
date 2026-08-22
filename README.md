# Chainlens (chainlens)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Chainlens, built by Web3 Labs, is a blockchain explorer and analytics platform for EVM-compatible public and private chains (Ethereum, Hyperledger Besu, Quorum, Polygon, Avalanche, BNB Chain, etc.) as well as Substrate-based chains. It combines a user-friendly block explorer with powerful REST APIs for real-time transaction monitoring, smart contract verification, token and NFT tracking (ERC-20, ERC-721, ERC-1155), and integration of on-chain data with existing analytics and reporting pipelines. The API follows the EIP-3091 block explorer route conventions and is offered both as SaaS and self-hosted.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chainlens/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chainlens/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analytics
- Blockchain
- Block Explorer
- Cryptocurrencies
- DeFi
- Ethereum
- EVM
- NFTs
- Smart Contracts
- Web3

## Timestamps

- **Created:** 2024-11-07
- **Modified:** 2026-05-19

## APIs

### Chainlens Blockchain Explorer API

The Chainlens REST API exposes block explorer data for EVM chains including transactions, internal transactions, events, blocks, addresses, tokens, NFTs, and smart contract metadata. Endpoints follow OpenAPI 3 conventions and the EIP-3091 block explorer route standard, supporting real-time on-chain analytics, wallet inspection, contract verification look-up, and reporting pipelines.

- **Human URL:** [https://www.chainlens.com/](https://www.chainlens.com/)
- **Base URL:** `https://api.chainlens.com`

#### Tags

- Blockchain
- Block Explorer
- EIP-3091
- Events
- NFTs
- Smart Contracts
- Tokens
- Transactions

#### Properties

- [Documentation](https://docs.chainlens.com/)
- [Overview](https://www.chainlens.com/features/blockchain-api)
- [OpenAPI](openapi/chainlens-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chainlens.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chainlens.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Specification](https://eips.ethereum.org/EIPS/eip-3091)

## Common Properties

- [Website](https://www.chainlens.com/)
- [Documentation](https://docs.chainlens.com/)
- [Getting Started](https://www.chainlens.com/documentation-categories/getting-started)
- [Sign Up](https://www.chainlens.com/free-sign-up)
- [Pricing](https://www.chainlens.com/plans)
- [Blog](https://www.chainlens.com/blog)
- [Git Hub](https://github.com/web3labs/chainlens-free)
- [Parent Company](https://www.web3labs.com/)
- [Contact](https://www.chainlens.com/contact)
- [Terms of Service](https://www.chainlens.com/terms)
- [Privacy Policy](https://www.chainlens.com/privacy-policy)
- [LinkedIn](https://www.linkedin.com/company/web3labs/)
- [X (Twitter)](https://x.com/web3labs)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Plans](undefined)
- [L L Ms Txt](https://docs.chainlens.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
