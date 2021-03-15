# {DRAFT} Decred Journal – {month} {year}

![{alt text}](../img/{file.jpg} "{hover tooltip text}")

_Image: {"$title by $author. $optional-description" for artwork, "$description" for photos}_

{ introduction, major news of the month ordered by impact, don't put any links here }

Contents:

- [Development](#development)
- [People](#people)
- [Governance](#governance)
- [Network](#network)
- [Integrations](#integrations)
- [Outreach](#outreach)
- [Events](#events)
- [Media](#media)
- [Community Discussions](#community-discussions)
- [Markets](#markets)
- [Relevant External](#relevant-external)

## Development

The work reported below has the "merged to master" status unless noted otherwise. It means that the work is completed, reviewed, and integrated into the source code that advanced users can [build and run](https://medium.com/@artikozel/the-decred-node-back-to-the-source-part-one-27d4576e7e1c), but is not yet available in release binaries for regular users.

{ hint: add below overview of activity for each project. add any other project that warrants a paragraph, drop projects without notable updates. for each project the order of reporting is: changes released > merged to master > started work > discussions and future plans }

**[dcrd](https://github.com/decred/dcrd)**

- {}

**[dcrwallet](https://github.com/decred/dcrwallet)**

- {}

**[dcrctl](https://github.com/decred/dcrctl)**

- {}

**[Decrediton](https://github.com/decred/decrediton)**

- {}

**[Politeia](https://github.com/decred/politeia)**

- {}

**[vspd](https://github.com/decred/vspd)**

- {}

**[dcrstakepool](https://github.com/decred/dcrstakepool)**

- {}

**[dcrpool](https://github.com/decred/dcrpool)**

- {}

**[dcrlnd](https://github.com/decred/dcrlnd)**

- {}

**[cspp](https://github.com/decred/cspp)**

- {}

**[dcrdex](https://github.com/decred/dcrdex)**

- {}

**[dcrandroid](https://github.com/planetdecred/dcrandroid)**

- {}

{ also check the base library https://github.com/planetdecred/dcrlibwallet }

**[dcrios](https://github.com/planetdecred/dcrios)**

- {}

**[godcr](https://github.com/planetdecred/godcr)**

- {}

**[dcrdata](https://github.com/decred/dcrdata)**

- {}

**[tinydecred](https://github.com/decred/tinydecred)**

- {}

**[dcrros](https://github.com/decred/dcrros)**

- {}

**[docs](https://github.com/decred/dcrdocs)**

- {}

**[dcrdevdocs](https://github.com/decred/dcrdevdocs)**

- {}

**[decred.org](https://github.com/decred/dcrweb)**

- {}

{ check if anything interesting happened in the other repos under

- https://github.com/decred
- https://github.com/planetdecred
- https://github.com/raedahgroup

}

Other:

- { smaller items go here }

## People

{ hint: list people who made their first non-trivial commits merged in master branches, in alphabetical order }

Welcome to new first time contributors with code merged to master: {@handle} ([{repo}]({link to user's commits})), ...

Congratulations to new contractors granted the Decred Contractor Clearance (DCC): [{@handle}]({link to most relevant account}). { hint: check the CMS }

{ welcome new corporate contractors with short intros, if any }

{ updates from existing contractors }

{ interviews about people }

Community stats as of {date}:

- Politeia users: {} (+{})
- [Twitter](https://twitter.com/decredproject) followers: {} (+{})
- [Reddit](https://www.reddit.com/r/decred/) subscribers: {} (+{})
- [Matrix](https://chat.decred.org/) #general users: {} (+{})
- [Discord](https://discord.gg/GJ2GXfz) users: {} (+{})
- [Telegram](https://t.me/Decred) users: {} (+{})
- [YouTube](https://www.youtube.com/decredchannel) subscribers: {} (+{}), views: {} (+{})
- GitHub [dcrd](https://github.com/decred/dcrd) stars: {} (+{}), forks: {} (+{})

## Governance

In {month} the [Treasury](https://explorer.dcrdata.org/address/Dcur2mcGjmENx4DhNqDctW5wJCVyT3Qeqkx) received {n} DCR and spent {n} DCR. Using {month}'s daily average DCR/USD rate of ${n.nn}, this is ${n}K received and ${n}K spent. At {prev month}'s average daily rate of ${n.nn}, the USD figure billed for past work is ${n}K. As of {date}, Treasury balance is {n} DCR ({n} million USD at ${n.nn}).

{ high level recap of decision-making activity and most important events }

- {}

{ check https://github.com/decredcommunity/proposals/commits/master for updates }

Politeia Digest [issue {}]({}) and [issue {}]({}) have more details on the month's proposals.

## Network

{ section hint: use the same `zoom` parameter for all dcrdata links }

**Hashrate**: {month}'s [hashrate](https://explorer.dcrdata.org/charts?chart=hashrate&zoom={t1}-{t2}&scale=linear&bin=block&axis=time) {set zoom to show the month} opened at ~{n} Ph/s and closed ~{n} Ph/s, bottoming at {n} Ph/s and peaking at {n} Ph/s throughout the month.

Pool hashrate [distribution](https://miningpoolstats.stream/decred) as of {date}: {PoolName n%, ...}.

Distribution of 1,000 blocks [mined](https://miningpoolstats.stream/decred) before {date}: {PoolName n%, ...}.

{ hint: fallback link for pool distribution: https://dcrstats.com/pow }

**Staking**: [Ticket price](https://explorer.dcrdata.org/charts?chart=ticket-price&zoom={t1}-{t2}&axis=time&visibility=true-true&mode=stepped) varied between {n.n}-{n.n} DCR, with 30-day [average](https://dcrstats.com/) at {n.n} DCR (+{n.n}). { use same t1-t2 for zoom }

The [locked amount](https://explorer.dcrdata.org/charts?chart=ticket-pool-value&zoom={t1}-{t2}&scale=linear&bin=block&axis=time) was {n.nn}-{n.nn} million DCR, meaning that {n.n}-{n.n}% of the circulating supply [participated](https://explorer.dcrdata.org/charts?chart=stake-participation&zoom={t1}-{t2}&scale=linear&bin=block&axis=time) in proof-of-stake.

{ recap of ticket price action if it was interesting }

**Nodes**: Throughout {month} there were around {n} reachable nodes according to [dcrextdata](https://dcrextdata.planetdecred.org/nodes). Version distribution: {n% app version, ...}.

{ maybe } The share of [mixed coins](https://explorer.dcrdata.org/charts?chart=coin-supply&zoom={t1}-{t2}&bin=day&axis=time&visibility=true-true-true) varied between {n.n}-{n.n}%.

{ maybe } Decred's [Lightning Network](https://ln-map.jholdstock.uk/) has seen {} nodes (+{}), {} channels (+{}) with a total capacity of {n.n} DCR (+{n.n}), as of {date}.

{ any interesting analysis or events in the network }

## Integrations

{ hint: new pieces of infrastructure or updates from existing: VSPs, exchanges, wallets, OTC desks, payment processors. use bullets or paragraphs, whatever looks best }

{ check https://github.com/decred/dcrwebapi/commits/master for changes to the VSP list }

{ check https://github.com/decred/dcrweb/commits/master to detect added/removed services }

Warning: the authors of the Decred Journal have no idea about the trustworthiness of any of the services above. Please do your own research before trusting your personal information or assets to any entity.

## Adoption

{ new merchants }

{ applications of Decred blockchain and related projects: Politeia, dcrtime, atomicswap }

{ investment adoption }

## Outreach

{ overview of outreach/communications/marketing/PR activity for past month and any short-term plans }

## Events

Attended:

- {dates} - [{title}]({event link}) - {city}, {country}. {recap}

Upcoming:

- {dates} - [{title}]({event link}) - {city}, {country}. {info}

{announcements in Events domain}

## Media

{ notable community efforts }

{ ratings news }

{ hint: use the following format: (title in Sentence case) by (author) ([domain](link)) - (optional comment) }

Selected articles:

- {}

Videos:

- {}

Audio:

- {}

Art/fun:

- {}

Translations:

- {}

Other non-English content:

- {}

## Community Discussions

Comm systems news:

- {}

{ selected discussed topics, as bullet list or one paragraph per topic }

Selected Reddit posts:

- {}

Selected Twitter discussions:

- {}

## Markets

In {month} DCR was trading between USD {n.nn}-{n.nn} / BTC {n.nnnnn}-{n.nnnnn}. The average daily rate was ${n.nn}.

{ markets overview: USD and BTC prices, highs and lows, interesting events, interesting analysis }

{ dcrdex updates, esp. volume }

## Relevant External

{ cc tech: PoW, ASIC resistance, full nodes, cc network security, etc }

{ governance, funding, chain forks, community splits }

{ DEX }

{ relevant exchanges and websites }

{ other: regulations, privacy, security, fun }

## About This Issue

This is issue {number} of Decred Journal. Index of all issues, mirrors, and translations is available [here](https://xaur.github.io/decred-news/).

Most information from third parties is relayed directly from source after a minimal sanity check. The authors of the Decred Journal have no ability to verify all claims. Please beware of scams and do your own research.

You can submit a story [here](https://github.com/xaur/decred-news/labels/next%20release) to be considered for the next release. [Feedback](https://github.com/xaur/decred-news/blob/docs/contributing.md#feedback) and [contributions](https://github.com/xaur/decred-news/blob/docs/contributing.md) are always welcome.

Credits (alphabetical order):

- writing and editing: {}
- reviews and feedback: {}
- title image: {}
- funding: Decred stakeholders
