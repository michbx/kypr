# kypr - nostr based Know Your Peer

Bitcoin is pseudo anonymous.  Not everyone want to open LN channels or enter into DLC contracts with everyone else.  

In centralised finance with counterparty risk, governments have imposed KYC - Know Your Customer - and CTF - Counter Terrorist Financing.  

For those who want to be choiceful about who they interact with, kypr enables decentralised KYC or KYP - Know Your Peer.  This concept was first raised by [p2pfiat](https://habla.news/u/p2p@getalby.com/93397547.policy-and-the-p2p-digital-value) and [Ray Youssef](https://x.com/ray_noOnes/status/1788077854732722414). 

Many KYP solution are possible. nostr enables on of the many solutions:
- People typically follow people they trust
- The people they trust, typically follow people they trust in turn

If Alice has Bob's npub, she can calculate how many people she follows, also follow Bob. This gives an indication of trust. 

This method is not perfect:
- Terrorists who also post about a topic that interests Alice or the people Alice follows, could still be qualified as trusted where Alice may in reality not be keen to interact with such peer
- Malicious actors can impersonate a trusted person and as such build a following among Alice or the people Alice follows

Further kypr development includes methods to report impersonators, ... that is the future.

Let's first build a prototype.
