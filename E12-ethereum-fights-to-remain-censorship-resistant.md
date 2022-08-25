# I, Degen - E12: Ethereum Fights to Remain Censorship Resistant - 8/24/2022

::: info
Listen at: idegen.fm 
:::

:::success
Contact us: [@idegenfm](https://twitter.com/idegenfm)
:::

#### Intro
Welcome to I, Degen - Each week, we track down and explore the most exciting crypto stories. Hacks, mysteries, exploits, and anything that feeds our crypto curiosity. We dig in, cutting through the misinformation and hype in search of a signal in the noise. 

#### Episode Summary
This week we have a bunch of weekly news updates. Then we take a deep dive into the upcoming Ethereum merge and rippling effects on Ethereum protocol level censorship from the OFAC Tornado Cash sanctions. 

# I,Degen - Weekly Stories

1.[The Chicago Mercantile Exchange (CME) Group will launch Ethereum option contracts on its platform on September 12. The company announced that it's waiting for regulatory review, and if approved, these new investment products will join its ETH futures and mini futures contracts.](https://bitcoinist.com/the-cme-launch-ethereum-options-ahead-of-the-merge/)

2.[Alleged Russian Money Launderer Extradited from the Netherlands to U.S.](https://www.justice.gov/opa/pr/alleged-russian-money-launderer-extradited-netherlands-us)
> According to court documents, Dubnikov and his co-conspirators laundered the proceeds of ransomware attacks on individuals and organizations throughout the United States and abroad. Specifically, Dubnikov and his accomplices laundered ransom payments extracted from victims of Ryuk ransomware attacks.

3.[Reaper Farm Yield Aggregator Owned](https://twitter.com/peckshield/status/1554423493390893057?s=12&t=rIQ0Bu1MzKT6I0UUQG8tyQ)

4.[TikTok monitoring all keyboard inputs and taps](https://krausefx.com/blog/announcing-inappbrowsercom-see-what-javascript-commands-get-executed-in-an-in-app-browser)
> When you open any link on the TikTok iOS app, it's opened inside their in-app browser. While interacting with the website, TikTok subscribes to all keyboard inputs (including passwords, credit card information, etc.) and every tap on the screen, like which buttons and links you click.

5.[Wrench Attack - 3 men targeted an Indian realtor they knew held bitcoin and abducted him while posing as sellers of a plot of land. They tortured him for 3 hours until he gave them 8 BTC.](https://timesofindia.indiatimes.com/city/lucknow/uttar-pradesh-three-take-rs-1-3-crore-ransom-in-bitcoins-from-realtor-held/articleshow/93603640.cms) - [[r/CryptoCurrency post](https://www.reddit.com/r/CryptoCurrency/comments/wt2rm6/3_men_targeted_an_indian_realtor_whom_they_knew/)]
* Victim was not hurt, according to his wife
* The suspect were caught using a trap to lure them back to the kidnapping spot 
Note: These attacks are rare but often receive much media attention. Nonetheless, it's important to be aware. Often, you see comments like, "yeah, this is why you keep your crypto a secret!", which happened on the Reddit post. However, is that advice practical for 'mainstream adoption?  

6.[Hackers steal crypto from Bitcoin ATMs by exploiting zero-day bug](https://www.bleepingcomputer.com/news/security/hackers-steal-crypto-from-bitcoin-atms-by-exploiting-zero-day-bug/) - via Bleepingcomputer, August 20, 2022 
> Hackers have exploited a zero-day vulnerability in General Bytes Bitcoin ATM servers to steal cryptocurrency from customers.

> When customers would deposit or purchase cryptocurrency via the ATM, the funds would instead be siphoned off by the hackers. 

> The attacker was able to create an admin user remotely via CAS administrative interface via a URL call on the page that is used for the default installation on the server and creating the first administration user. This vulnerability has been present in CAS software since version December 2020. 
[General Bytes Official Advisory](https://generalbytes.atlassian.net/wiki/spaces/ESD/pages/2785509377/Security+Incident+August+18th+2022)

7.[iOS VPNS have leaked traffic for years, Proton CEO says.](https://arstechnica.com/information-technology/2022/08/ios-vpns-still-leak-traffic-more-than-2-years-later-researcher-claims/)
* Apple notified more than two years ago
* claim/issue: any connections established BEFORE activating the VPN are not tunneled
* janky trick that may or may not fully work: Turn on your VPN, then turn on airplane mode off and on.  


8.[U.S. Lawmaker Questions Treasury Over Tornado Cash Sanctions](https://cryptobriefing.com/u-s-lawmaker-questions-treasury-over-tornado-cash-sanctions/) August 23, 2022  via CryptoBriefing.com  
> Rep. Tom Emmer (R-MN) raised questions over the decision to sanction Tornado Cash in a letter sent to the Treasury Department today.

> Emmer called the ban of a "neutral, open-source, decentralized technology" a "divergence" from historical precedent.

> Among other things, Emmer asked what recourse law-abiding users of Tornado Cash may have to claim funds trapped in the protocol. 

# I, Degen - Deep Dive - The Merge & Ethereum censorship in a post-sanctioned TC world

**What is the merge TLDR?**
> The Merge represents the joining of the existing execution layer of Ethereum (the Mainnet we use today) with its new proof-of-stake consensus layer, the Beacon Chain. It eliminates the need for energy-intensive mining and instead secures the network using staked ETH. A truly exciting step in realizing the Ethereum vision – more scalability, security, and sustainability.

`- https://ethereum.org/en/upgrades/merge/`

**Whats the problem?**
OFAC Tornado Cash sanctions fallout continues. 
> Ethermine, the largest Ethereum pool, has refused to pack Tornado Cash-related transactions into blocks in the past week. Several pool technicians also confirmed the news and said it was the first time in history.
>  
`— @WUBLOCKCHAIN AUGUST 20, 2022 - https://t.co/XLC3ZjddLR`

> Individual miners can refuse to include whatever they want, but it has little effect; the transaction just gets into the next block.
> Need a 51% attack (so, reverting blocks and not just excluding txs) to fully prevent txs from being included.

    — @VitalikButerin August 19, 2022

[The Case for Social Slashing](https://ercwl.medium.com/the-case-for-social-slashing-59277ff4d9c7) <-- Best dive in Ethereum Censorship via OFAC 


> So, what's the issue here?

> Well, one of the absolute core purposes for blockchains such as Ethereum is to provide neutrality and censorship resistance. That's why we tolerate that the system is slow and expensive to use at times—because of these unique qualities. A threat to censorship resistance is a threat to the system's raison d’être.

**Other censorship & merge-related stuff**
[Centralized censorship of privacy protocols outside of Tornado Cash](https://twitter.com/wublockchain/status/1560417501053616131?s=21&t=8gvk3CMPIhQ-gH59rw4Txg)
>Recently, FTX froze a user account who sent coins to @aztecnetwork's zkmoney. According to FTX, Aztec Connect - Aztec network / zk money has been identified as a mixing service, which is a high-risk activity prohibited by FTX.
 ![](https://hackmd.io/_uploads/HJSX467Js.png)

* [Tax implications of the merge ETH POW fork](https://www.reddit.com/r/ethereum/comments/wrr8t4/the_irs_is_going_to_have_a_field_day_if_ethpow/)

* [Most PoW miners intend to mine Ergo, not Ravencoin or Ethereum Classic post-Merge](https://www.reddit.com/r/CryptoCurrency/comments/wvl7gl/most_pow_miners_intend_to_mine_ergo_not_ravencoin/)

# I, Degen - Personal Hack Attempt of the Week
Zak: Just more Pig Butchering Telegram DM scams
Hunt's mom: email scams to get her coins

# E12 References & other links
**[Reminder - US law enforcement can legally use stingrays and does not require a probable cause warrant](https://www.reddit.com/r/privacy/comments/wt65g5/til_us_law_enforcement_can_legally_use_stingrays/)**

If you're interested in this check out Season 1, Episode 3 of Truth and Power on Netflix.  

> Daniel Rigmaiden- a brilliant, young scam artist turned whistleblower-evades the FBI for months after being accused of filing fraudulent tax claims and illegally collecting hundreds of thousands of dollars from the IRS. After being tracked down and arrested by the feds, Daniel becomes convinced his location was identified through illicit means. 

* [IPFS use outside blockchain and NFTs?](https://www.reddit.com/r/cuboulder/comments/wuzp5i/how_to_get_your_textbook_for_free_definitely/)
* [3AC Bought DickButt NFT?](https://www.reddit.com/r/CryptoCurrency/comments/vy84rw/3ac_borrowed_millions_from_voyagerblockfi_user/)

Show image courtesy of [3AC on OpenSea](https://opensea.io/assets/ethereum/0x42069abfe407c60cf4ae4112bedead391dba1cdb/1462)

Updating to test fix for strange github push/commit author issue. 

:::warning
We do our best to report accurately on the topics we discuss, but we're not always going to get everything right. Please comment here or reach out to us @idegenfm with corrections or comments!
:::
