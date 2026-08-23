I write defender-side invariant harnesses: recurring bug classes encoded as properties, each shipped
as a clean reference where the invariant holds and a planted-bug twin where it fires, both running in
CI on every push.

Solana and Anchor now, EVM alongside it, Cairo before that.

The tools are under [CaliperForge](https://github.com/caliperforge) and pinned below.

Upstream I have patches open against
[`solana-foundation/surfpool`](https://github.com/solana-foundation/surfpool),
[`solana-foundation/pay-kit`](https://github.com/solana-foundation/pay-kit) and
[`a16z/halmos`](https://github.com/a16z/halmos).
[Everything I have opened, and where each one currently stands.](https://github.com/search?q=is%3Apr+author%3Amichael-moffett&type=pullrequests)

CaliperForge is an AI research studio and the work is agent-assisted. I review every load-bearing
decision, run the reproductions in a cold environment, and ship under my own name.

[caliperforge.com](https://caliperforge.com)
