# Content sources

Reviewed October 3, 2026. Project descriptions are based on public repositories and project-author corrections; Kamui’s architecture document is linked separately. Product captures are authentic; no generated product interfaces are used.

| Project | Source | Visual |
| --- | --- | --- |
| Oreka | https://github.com/mangekyou-labs/oreka | Cropped from the highest available 3456 × 2160 video at https://youtu.be/3SbgZNxx3wU; frame at 4:03 showing market outcome, position chart, and trading controls |
| Haze API | https://github.com/mangekyou-labs/haze-api | Exact user-supplied terminal capture, showing a client response through ZK Credits. It does not independently establish proof verification or billing correctness. |
| Chakra | https://github.com/mangekyou-labs/chakra | Live browser capture after entering 100 USDC and receiving 113.927499 EURC via presto-hub, on Arc testnet |
| Kamui | https://github.com/mangekyou-labs/kamui; [technical architecture](https://docs.google.com/document/d/1nKmlUuggSQDxrbMSGgY1MRPvZ82dzyD_DYwT4Osuow4/edit?usp=sharing) | Cropped from the supplied 1736 × 1080 demo at https://youtu.be/fqdy0rccu-Q, frame at 2:22; crop x=502, y=164, width=732, height=712 shows a fulfilled request with 92,398, dice roll 6, Tails, and expanded VRF output. |
| MGK Exchange | https://github.com/mangekyou-labs/mgk-protocol | Live capture of https://mgkprotocol.vercel.app/trade with chart and order book. Devnet interface only; no executed trade claimed. |

## Open-source contributions

- ERC-1155 integration: merged https://github.com/turbo-eth/template-web3-app/pull/156 (also PR 143).
- IOTA GraphQL refactor: https://github.com/iotaledger/iota-rust-sdk/pull/1016. Merge timestamp is absent; portfolio labels this a pull request, not a verified merge.
- Solana wallet dependencies: https://github.com/MrSufferer/spl-token-wallet/tree/fix/outdated-packages. Upstream merge was not found; portfolio links the contribution branch.
- Magick cloning plugin: merged https://github.com/Oneirocom/Magick/pull/333; selection compatibility in merged PR 377.

User-provided contributions are included with their actual accessible references. Merge labels are reserved for verified merged PRs.

Oreka’s permissionless ICP mainnet positioning was supplied by the project author. Network labels are consolidated in the project note rather than repeated in headings and captions.

Kamui’s completed Solana implementation and first elliptic-curve VRF verification milestone were supplied by the project author. The demo provides the fulfilled UI capture; the architecture document describes the design and is not used to characterize the implementation as proposed.
