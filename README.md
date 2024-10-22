# Blockspace and Execution Commitments Aggregated Links

- _Blockspace commitments_: guarantees with respect to blockspace and its related capacity for transaction inclusion into future blocks. Blockspace derivatives are an example of a blockspace commitment.
- _Execution commitments_: guarantees with respect to state updates on the requested inputs to deliver the target state. Coprocessors are an example of an execution commitment device.

## Blockspace Commitments

### Pre-confirmations

Not all pre-confirmations are equal. The different strength of pre-confs lie on a spectrum of weak basic inclusion guarantees to stronger post-execution stateful guarantees (h/t [Jon Charb](https://x.com/jon_charb)).

[We're All Building the Same Thing](https://dba.xyz/were-all-building-the-same-thing/#Preconfirmations) - Jon Charbonneau, Jun 2024

[Preconfirmations for Vanilla Based Rollups](https://hackmd.io/@Perseverance/rJ0nun5yR) - George Spasov, Apr 2024

[Epochs and slots all the way down: ways to give Ethereum users faster transaction confirmation times](https://vitalik.eth.limo/general/2024/06/30/epochslot.html) - Vitalik, Jun 2024

[Preconfirmations: The Fulfillment-Delivery Paradigm](https://mirror.xyz/preconf.eth/sgcuSbd1jgaRXj9odSJW-_OlWIg6jcDREw1hUJnXtgI) - Primev, Feb 2024

[Commitment Games and Where to Find Them](https://mirror.xyz/preconf.eth/3SXageNPpcQMz8L2YfW5ipvthNl-InPzaPAfb3LxwqA) – Primev, Jun 2024

[Credible Commitments: How Pre-Confirmations Unlock L2 Interoperability](https://www.youtube.com/watch?v=QpJm0IO_foU&ab_channel=BellCurve) - Jonas and Murat (Bell Curve), Mar 2024

[How AVSs Enable Scalable, Secure and Customizable Execution](https://www.youtube.com/watch?v=nPgxoZHrCIU&ab_channel=BellCurve) - Ludwig and Muto (Bell Curve), Jun 2024

[Standard Preconfirmations and Execution Preconfirmations via Intents](https://www.youtube.com/watch?v=4UiH7PqJPQI&ab_channel=Osmosis) – Dev Ojha, Jun 2024

[Preconfirmations for transactions on L2](https://review.stanfordblockchain.xyz/i/146232834/the-current-state-of-rollups) – Stanford Blockchain, Jul 2024

[Beyond Spot Transactions: Modeling Dynamic Preconfirmation Auctions](https://mirror.xyz/preconf.eth/iPfGsj55-C-D13hyrj_hj2tHAKU7xzeqltZ6gIum3j4) – Primev, Apr 2024

[Un-confirming "Pre-confirmations"](https://eljhfx.substack.com/p/un-confirming-pre-confirmations) - Elijah, Jun 2024

[Blob Preconfirmations with Inclusion Lists to Mitigate Blob Contention and Censorship](https://ethresear.ch/t/blob-preconfirmations-with-inclusion-lists-to-mitigate-blob-contention-and-censorship/19150) - Christian Matt, Mar 2024

[Evaluating Preconfirmations](https://www.youtube.com/watch?v=Qsl2b7agX7Q&list=PLFRYxG8q7EY59UlLI-FXMC3si9icQmcDL&index=13&ab_channel=SevenXVentures) - Ellie Davidson, Mar 2024

[Don’t Overload the Proposer](https://streameth.org/zuberlin/watch?session=666af08807f92b086c2c2e54) – Vitalik, Jun 2024

[Based proposer commitments - Ethereum’s marketplace for proposer commitments](https://ethresear.ch/t/based-proposer-commitments-ethereum-s-marketplace-for-proposer-commitments/19517?u=drewvanderwerff) - Drew Van der Werff, May 2024

[Ethereum Sequencing and Preconfirms Call Notes](https://docs.google.com/document/d/1FG3nKQdUNb_YHCp_IzSDkC_r7A6HOT11O2YNUjCX-6s/edit#heading=h.2whbk0my4lq5) – Drew Van der Werff and Sam Jernigan, Mar 2024

[Lido + Preconfs](https://docs.google.com/presentation/d/1S4QseT2nTdliTmSIoPtel5UKNlJ467iPbB_W0D2tuRw/edit#slide=id.g2dabf726cd7_0_113) - Sacha (Lido), May 2024

[Preconfirmation-Based Market Manipulation](https://docs.google.com/presentation/d/1y9OhyQuJ0qJP1s-WyKbdNF_qrk3Nn_cyAVDefC0d1_Y/edit#slide=id.p) - Alex Watts (Fastlane), Feb 2024

[Keynote: Rollup Preconfirmations](https://www.youtube.com/watch?v=boxGqp9mGJ4&ab_channel=Altlayer) - Justin Drake, May 2024

[Preconf.wtf](http://preconf.wtf/) - Zuberlin MEV Day, Jun 2024

[Based Preconfirmations](https://ethresear.ch/t/based-preconfirmations/17353) – Justin Drake, Nov 2023

[Ethereum Sequencing and Preconfirmations Calls](https://www.youtube.com/watch?v=fbyy_IHo-lI&list=PLJqWcTqh_zKHDFarAcF29QfdMlUpReZrR&ab_channel=Ethereum) - Ethereum, Ongoing

[Strawmanning Based Preconfirmations](https://ethresear.ch/t/strawmanning-based-preconfirmations/19695) – Lin Oshitani (Nethermind Research), May 2024

[BFT & Proposer-Promised Preconfirmations](https://hackmd.io/@EspressoSystems/bft-and-proposer-promised-preconfirmations) – Espresso, Dec 2023

[Awesome Preconfirmations (ZuBerlin)](https://github.com/NethermindEth/awesome-preconfirmations) - Nethermind, Jun 2024

### Blockspace Derivatives

[Structuring Blockspace Derivatives](https://mirror.xyz/0x03c29504CEcCa30B93FF5774183a1358D41fbeB1/WKa3GFC03uY34d2MufTyD0c595xVRUEZi9RNG-dHNKs) – Julian Ma, Oct 2022

[Opportunities and Considerations of Ethereum’s Blockspace Future](https://frontier.tech/ethereums-blockspace-future) – Drew Van der Werff and Alex Matthews, Jul 2023

[Structuring Blobspace Futures](https://mirror.xyz/tamaratran.eth/6ezSVdmxWv2yN8a2hm_NlJtRSWOm1ql1eRU6Fbv2xfY) - Tamara Tran, May 2024

<!-- ### Block Distribution Mechanisms

https://ethresear.ch/t/on-block-space-distribution-mechanisms/19764#Block-space-distribution-today

https://ethresear.ch/t/execution-auctions-as-an-alternative-to-execution-tickets/19894

https://mirror.xyz/barnabe.eth/QJ6W0mmyOwjec-2zuH6lZb0iEI2aYFB9gE-LHWIMzjQ

https://ethresear.ch/t/mev-resistant-dynamic-pricing-auction-of-execution-proposal-rights/20024

https://ethresear.ch/t/execution-tickets/17944 -->

### Coprocessors

[A Brief Intro to Coprocessors](https://crypto.mirror.xyz/BFqUfBNVZrqYau3Vz9WJ-BACw5FT3W30iUX3mPlKxtA) - Emperor, Oct 2023

[Off-Chain Compute is All You Need](https://crypto.mirror.xyz/8TXa9EqNkwjnQNenXscPwyHC6V99dmyhcO7uPYbeaIo) - Emperor and Krane, Nov 2023

[Cryptoeconomic coprocessors (thread)](https://x.com/sreeramkannan/status/1730310412904599714) – Sreeram Kannan, Nov 2023

[What is a ZK Coprocessor?](https://blog.axiom.xyz/what-is-a-zk-coprocessor/) – Camila Ramos and Yi Sun, Oct 2023

[Verifiable Off-Chain Compute](https://florindigital.substack.com/p/verifiable-off-chain-compute-enabling) - Florin Digital, Jun 2024

## Insurance (Commitment-Adjacent)

[Stakesure Talk by Sreeram](https://www.youtube.com/watch?v=UeZIxcLaH00&ab_channel=Nethermind) – Sreeram Kannan, Nov 2023

[Stakesure Paper](https://arxiv.org/abs/2401.05797) - Soubhik Deb, Robert Raynor, and Sreeram Kannan, Jan 2024
