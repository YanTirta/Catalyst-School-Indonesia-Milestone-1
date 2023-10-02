# **Fund10 parameters**

Fund10 Operating parameters are the actual operating parameters that make up the Catalyst voting protocol put in place to enable the community to decide which proposal will receive funding from the Cardano Treasury.

### **Table 1**

This table summarizes main parameters to be used.

| NUM | PARAMETER | VALUE | DESCRIPTION |
|:--:|:--|:--|:--|
||Product/Business/Informative Parameters|
|A1|Direct Voting privacy state|Yes|Are votes private?|
|A2|Fund name|Fund10|  
|A3|Funds under control|50,000,000 ada|Fund will control 50M ada|
|A4|Challenges title and budget|[Development & Infrastructure](https://cardano.ideascale.com/a/dtd/414308-48088) - ₳8,685,600<p>&nbsp;</p>[Startups & Onboarding for Students](https://cardano.ideascale.com/a/dtd/422445-48088) - ₳394,800<p>&nbsp;</p>[Products & Integrations](https://cardano.ideascale.com/a/dtd/414299-48088) - ₳9,080,400<p>&nbsp;</p>[OSDE: Open Source Dev Ecosystem](https://cardano.ideascale.com/a/dtd/421335-48088) - ₳3,158,400<p>&nbsp;</p>[SPO Tools & Community Projects](https://cardano.ideascale.com/a/dtd/414105-48088) - ₳4,737,600<p>&nbsp;</p>[Developer Ecosystem - The Evolution](https://cardano.ideascale.com/a/dtd/422540-48088) - ₳6,316,800<p>&nbsp;</p>[DAOs <3 Cardano](https://cardano.ideascale.com/a/dtd/420431-48088) - ₳3,158,400<p>&nbsp;</p>Atala PRISM: Launch Ecosystem🚀  - ₳3,158,400<p>&nbsp;</p>[dRep improvement and onboarding](https://cardano.ideascale.com/a/dtd/418533-48088) - ₳394,800<p>&nbsp;</p>[Building on NMKR](https://cardano.ideascale.com/a/dtd/419498-48088) - ₳394,800<p>&nbsp;</p>[Catalyst Open](https://cardano.ideascale.com/c/campaigns/379/about) - ₳1,400,000<p>&nbsp;</p>[Catalyst Fund Operations](https://cardano.ideascale.com/c/campaigns/380/about) - ₳2,140,000<p>&nbsp;</p>[Catalyst System Improvements](https://cardano.ideascale.com/c/campaigns/381/about) - ₳3,570,000
|A5|Minimum budget request per proposal|₳15,000|Minimum amount for each proposal|
|A6|Maximum budget request per proposal (applies to Catalyst Open category only)|₳75,000|Maximum amount for each proposal in  the Catalyst Open category|
|A7|Proposals submission fee|Free|Proposers can submit any number of proposals for discussion on Ideascale. Catalyst Team will remove ‘placeholder’ proposals at the point where the submission deadline elapses. Placeholder proposals include proposals where any of the form fields are left unanswered or obviously incomplete by the deadline|
|A8|Funds Move Instantaneous Rewards (MIR) target date|Sep 18, 2023|Fund10 budget should be moved from the treasury to the seed account before voting results|
|A9|Rewards and funds distribution target date|Oct 16, 2023- Oct 20, 2023|When community rewards  and F10 funding for initial  milestone 1 tranche is paid following verification of test transaction|
|A10|Maximum proposals that can be put on the ballot|No limit|
|A11|Community Reviewer registration|Through Ideascale|Anyone can register as a Community Reviewer.<p>&nbsp;</p>Community Reviewers will be delineated between Lv0, Lv1, Lv2 reviewers based on their contributions during the Community Review stage|
|A12|Proposals registration on the blockchain|Aug 30, 2023|Date when proposals are loaded into the vote plan and registered into Block0|
|A13|Voting power threshold|Minimum 450,000,000 lovelace (450 ada)<p>&nbsp;</p>Recommended 500,000,000 lovelace (500 ada)|450 ada is the minimum stake threshold to become a voter, based on the efficiency benchmarks of the voting protocol<p>&nbsp;</p>Specific value of the voting stake threshold will be defined by the protocol benchmarks<p>&nbsp;</p>Please note that due to the variety of 3rd party wallet providers integrating with Catalyst and associated voter registration fees, the recommended threshold to communicate is 500 ada required to participate in Catalyst voting as a buffer to account for unclaimed staking rewards|
|A14|Registration snapshot date|Aug 18, 2023 09:00 PM UTC
|A15|Voting period start time|Aug 31, 2023, 11:00 AM UTC|UTC date and time when voters can start voting on proposals
|A16|Voting period end time|Sep 14, 2023, 11:00AM UTC
|A17|Start of tallying|Sep 14, 2023
|A18|End of tallying|Sep 18, 2023|UTC date when  the decrypted tally is made publicly available
|A19|fund_id|10|Fund_id as described in vote plan
|A20|Tallying optimization|1 ADA = 1 voting token (i.e. the stake amount in lovelace is divided by 1000000)|How voting power is being proportionally reduced in order to optimize tallying performance
||Rewards Parameters
|B1|Proposal Funding logic (winner selection rule)|Fuzzy threshold voting, proposals are ranked by the difference of Yes and No votes and funded one by one until challenge budget is exhausted|Proposals are ranked by sum of votes and funded in order. If the amount requested by a  proposal is larger than the remaining challenge amount, it is skipped
|B2|Proposal acceptance threshold|1% of total voting power<p>&nbsp;</p>15% more ‘Yes’ than ‘No’|At least 1% of the total registered stake must vote on a proposal.<p>&nbsp;</p>E.g., there is 1 billion ADA as a total registered stake. To be accepted (become an ‘approved proposal’ as well as be eligible for funding), a proposal must be voted by at least 0.01 * (1 * 10^9) = 10 millions of ADA.<p>&nbsp;</p>'Yes'-'No' difference of the stake voted on proposal must be at least 15%.<p>&nbsp;</p>Formula: (YES-NO)/(YES+NO) > 0.15<p>&nbsp;</p>(e.g., 90% 'Yes' and 10% 'No', or 57.6% 'Yes' and 42.4% 'No', or 100% 'Yes' and 0% 'No', etc.; it is assumed that abstained stake does not vote on the proposal in the current architecture
|B3|Voting options and Funding logic in Catalyst Operations category|Yes/Abstain<p>&nbsp;</p>‘No’ option<p>&nbsp;</p>No thresholds|The winner is determined by the highest ‘Yes’ vote only
