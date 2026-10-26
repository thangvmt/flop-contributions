# FLOP contributions

A dated index of what I have contributed around [FLOP](https://flop.finance) and [Technocore](https://technocore.chat): specification feedback, service issues, measurements, contest entries and writing. Every item is a link to the original, so anything here can be checked at the source.

I am [@tatthang](https://x.com/tatthang) on X and [thangvmt](https://github.com/thangvmt) on GitHub. This is a personal record. It is not affiliated with or endorsed by Flop Labs, and nothing in it is a claim about rewards or eligibility.

All dates are UTC; statuses checked on **2026-10-26**. Issues move, so the link is the source of truth.

## Specification feedback: `flop-labs/yellowpaper`

| Opened | Item | Status | What it is |
|---|---|---|---|
| 2026-10-19 | [#172](https://github.com/flop-labs/yellowpaper/issues/172) | open | Reports a settled devnet gateway session whose channel agent differed from the enrolled wallet, and asks which account receives R8.4 credit. Other contributors have since pointed to the open spec items (E.38, E.40) and to the unlock rules (R8.7, R8.8) that tie Agent grant unlock to the account funding the channel. |
| 2026-10-19 | [#171](https://github.com/flop-labs/yellowpaper/issues/171) | closed (completed) | The docs FAQ said nothing is burned anywhere, while Appendix A and the devnet runtime burned 10% of the inclusion fee. The hosted Yellow Paper has since adopted zero burn (D-0529), as other contributors noted on the thread. Closed on 2026-10-26: the 0.5.0 (draft) sync sets the fee burn to 0% and the validator page was corrected. |
| 2026-10-07 | [#128](https://github.com/flop-labs/yellowpaper/issues/128) | open | The validator hardware profile in §15.3 and on the testnet page disagree (RAM, ECC, storage floor). |

## Service and protocol: `flop-labs/technocore-chat` and `flop-labs/tclk`

| Opened | Item | Status | What it is |
|---|---|---|---|
| 2026-09-04 | [tclk#89](https://github.com/flop-labs/tclk/issues/89) | open | Board counts by the `tclk1 ` prefix ran about 38% high in the reported sample, because one fleet emitted a dialect the decoder rejects. |
| 2026-09-04 | [tclk PR #94](https://github.com/flop-labs/tclk/pull/94) | closed (not merged) | Proposed a transcript-gap diagnostic; closed, not merged, at my suggestion in favour of #97. |
| 2026-08-30 | [technocore-chat#565](https://github.com/flop-labs/technocore-chat/issues/565) | closed | `?since=` past the head was echoed back and printed as `next:`. |
| 2026-08-27 | [technocore-chat PR #384](https://github.com/flop-labs/technocore-chat/pull/384) | closed (not merged) | Docs: `first_seq` above `since+1` does not mean the ring dropped anything. Closed as a duplicate of #974; the maintainer quoted its causation wording in a comment on that PR. |
| 2026-08-25 | [technocore-chat#199](https://github.com/flop-labs/technocore-chat/issues/199) | open | Measuring the `did/` namespace at its cap: about 4% of slots could not answer a DID lookup in the reported sample. |

## Measurements

- [thangvmt/technocore-measured](https://github.com/thangvmt/technocore-measured): dated measurements of technocore.chat with reproduction scripts and stated limits. A scheduled job updates its watch snapshots; historical measurements retain their original dates. Listed in [zunmax/awesome-technocore](https://github.com/zunmax/awesome-technocore), and proposed for [pucedoteth/awesome-technocore-verified](https://github.com/pucedoteth/awesome-technocore-verified/pull/1).

## Contests

- **Technocore Sonnet Challenge (sonnet-2)** (September 2026): participated with a team; published a write-up of submission failure modes from the signed rooms: [post](https://x.com/tatthang/status/2100071939746529669).
- **Technocore Close Call Challenge (close-1)** (September to October 2026): operated agents during the challenge and published five lessons from the run: [post](https://x.com/tatthang/status/2105536922953421071).

## Writing on X

Newest first. A selected personal index, not a complete archive.

Historical posts, reflecting the information and my understanding at publication. They are not current onboarding instructions, eligibility rules, or evidence of rewards.

| Date | Post | About |
|---|---|---|
| 2026-10-19 | [link](https://x.com/tatthang/status/2112139226011865225) | My post on the provisional November 3 testnet date and launch timeline, citing FLOP's docs FAQ ([source](https://docs.flop.network/docs/testnet-and-timeline), updated 2026-10-16). |
| 2026-10-13 | [link](https://x.com/tatthang/status/2109997063362806268) | How the 4.4B testnet airdrop splits across miners, validators, agents and the ecosystem reserve. |
| 2026-10-12 | [link](https://x.com/tatthang/status/2109777289991123291) | What the 25% testnet allocation means, from the CSO's answers at the launch event. |
| 2026-10-09 | [link](https://x.com/tatthang/status/2108511467066818632) | FLOP's launch model compared with Bitcoin's early mining: no seed round, no VC allocation. |
| 2026-10-04 | [link](https://x.com/tatthang/status/2106774211239022739) | What the Close Call contest showed about bot fleets and the network under load. |
| 2026-10-01 | [link](https://x.com/tatthang/status/2105536922953421071) | Five rules learned from running agents in Close Call. |
| 2026-09-30 | [link](https://x.com/tatthang/status/2105119392644354543) | Arthur Hayes on why holding FLOP is a bet on agents, not human attention. |
| 2026-09-17 | [link](https://x.com/tatthang/status/2100499416709030231) | The core thesis: agents need money that converts directly into compute. |
| 2026-09-16 | [link](https://x.com/tatthang/status/2100071939746529669) | Why most Sonnet submissions were rejected, read from the signed rooms. |
| 2026-09-11 | [link](https://x.com/tatthang/status/2098465800688677231) | How to enter the Sonnet contest in five steps. |
| 2026-09-10 | [link](https://x.com/tatthang/status/2097971756573347848) | What a Yellow Paper revision changed for anyone pricing GPUs around FLOP. |
| 2026-09-08 | [link](https://x.com/tatthang/status/2097194885996773491) | Arthur Hayes on why a compute spot market alone would not justify a high valuation. |
| 2026-09-07 | [link](https://x.com/tatthang/status/2096989162448781560) | The first published airdrop split, and which group had published criteria. |
| 2026-09-06 | [article](https://x.com/tatthang/status/2096445135970271302) | The FLOP Deal Playbook: why a DID earns nothing on its own. |
| 2026-09-06 | [link](https://x.com/tatthang/status/2096503857228784051) | Agents that die when the laptop closes, and why persistent memory matters. |
| 2026-09-03 | [link](https://x.com/tatthang/status/2095443848864596123) | Why most testnet farmers are expected to be disqualified. |
| 2026-09-03 | [link](https://x.com/tatthang/status/2095372921686663508) | The escrow protocol that lets two agents trade when neither wants to go first. |
| 2026-09-02 | [link](https://x.com/tatthang/status/2095021160979423726) | Notes from the tokenomics AMA and what they mean for the airdrop. |
| 2026-09-01 | [link](https://x.com/tatthang/status/2094639965586243638) | A sample of 80 agents that had claimed Technocore rooms, and what it showed about farming for the airdrop. |
| 2026-08-30 | [link](https://x.com/tatthang/status/2093918035887390760) | Why Arthur Hayes treats a $10B valuation as the small outcome. |
| 2026-08-29 | [link](https://x.com/tatthang/status/2093509129054851217) | What Technocore's published "liveness" numbers measure, and what they do not. |
| 2026-08-28 | [link](https://x.com/tatthang/status/2093391001964659176) | Measuring the FLOP Chip logo file. |
| 2026-08-26 | [link](https://x.com/tatthang/status/2092475626158739878) | "What the hell is FLOP?": Arthur Hayes on Pomp's podcast. |
| 2026-08-25 | [link](https://x.com/tatthang/status/2092264173178933406) | What Arthur Hayes confirmed about how the airdrop and faucet would work. |
| 2026-08-24 | [article](https://x.com/tatthang/status/2091894656191864981) | The FLOP Airdrop Playbook: onboarding a first AI agent. |
| 2026-08-24 | [link](https://x.com/tatthang/status/2091866440551002448) | How to onboard an AI agent to Technocore in four steps. |
| 2026-08-24 | [link](https://x.com/tatthang/status/2091771207914049939) | Two observations from FLOP's first week. |
| 2026-08-21 | [link](https://x.com/tatthang/status/2090672676943929376) | A plain breakdown of Arthur Hayes's first long interview about FLOP. |

## How this is kept

Updated by hand when something new is published or an item changes status. If a link here disagrees with the original, the original wins.
