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
|A5|Minimum budget request per proposal|₳15,000|Minimum amount for each proposal
|A6|Maximum budget request per proposal (applies to Catalyst Open category only)|₳75,000|Maximum amount for each proposal in  the Catalyst Open category
|A7|Proposals submission fee|Free|Proposers can submit any number of proposals for discussion on Ideascale. Catalyst Team will remove ‘placeholder’ proposals at the point where the submission deadline elapses. Placeholder proposals include proposals where any of the form fields are left unanswered or obviously incomplete by the deadline
|A8|Funds Move Instantaneous Rewards (MIR) target date|Sep 18, 2023|Fund10 budget should be moved from the treasury to the seed account before voting results
|A9|Rewards and funds distribution target date|Oct 16, 2023- Oct 20, 2023|When community rewards  and F10 funding for initial  milestone 1 tranche is paid following verification of test transaction
|A10|Maximum proposals that can be put on the ballot|No limit
|A11|Community Reviewer registration|Through Ideascale|Anyone can register as a Community Reviewer<p>&nbsp;</p>Community Reviewers will be delineated between Lv0, Lv1, Lv2 reviewers based on their contributions during the Community Review stage
|A12|Proposals registration on the blockchain|Aug 30, 2023|Date when proposals are loaded into the vote plan and registered into Block0
|A13|Voting power threshold|Minimum 450,000,000 lovelace (450 ada)<p>&nbsp;</p>Recommended 500,000,000 lovelace (500 ada)|450 ada is the minimum stake threshold to become a voter, based on the efficiency benchmarks of the voting protocol<p>&nbsp;</p>Specific value of the voting stake threshold will be defined by the protocol benchmarks<p>&nbsp;</p>Please note that due to the variety of 3rd party wallet providers integrating with Catalyst and associated voter registration fees, the recommended threshold to communicate is 500 ada required to participate in Catalyst voting as a buffer to account for unclaimed staking rewards
|A14|Registration snapshot date|Aug 18, 2023 09:00 PM UTC
|A15|Voting period start time|Aug 31, 2023, 11:00 AM UTC|UTC date and time when voters can start voting on proposals
|A16|Voting period end time|Sep 14, 2023, 11:00AM UTC
|A17|Start of tallying|Sep 14, 2023
|A18|End of tallying|Sep 18, 2023|UTC date when  the decrypted tally is made publicly available
|A19|fund_id|10|Fund_id as described in vote plan
|A20|Tallying optimization|1 ADA = 1 voting token (i.e. the stake amount in lovelace is divided by 1000000)|How voting power is being proportionally reduced in order to optimize tallying performance
||Rewards Parameters
|B1|Proposal Funding logic (winner selection rule)|Fuzzy threshold voting, proposals are ranked by the difference of Yes and No votes and funded one by one until challenge budget is exhausted|Proposals are ranked by sum of votes and funded in order. If the amount requested by a  proposal is larger than the remaining challenge amount, it is skipped
|B2|Proposal acceptance threshold|1% of total voting power<p>&nbsp;</p>15% more ‘Yes’ than ‘No’|At least 1% of the total registered stake must vote on a proposal<p>&nbsp;</p>E.g., there is 1 billion ADA as a total registered stake. To be accepted (become an ‘approved proposal’ as well as be eligible for funding), a proposal must be voted by at least 0.01 * (1 * 10^9) = 10 millions of ADA<p>&nbsp;</p>'Yes'-'No' difference of the stake voted on proposal must be at least 15%.<p>&nbsp;</p>Formula: (YES-NO)/(YES+NO) > 0.15<p>&nbsp;</p>(e.g., 90% 'Yes' and 10% 'No', or 57.6% 'Yes' and 42.4% 'No', or 100% 'Yes' and 0% 'No', etc.; it is assumed that abstained stake does not vote on the proposal in the current architecture
|B3|Voting options and Funding logic in Catalyst Operations category|Yes/Abstain<br>‘No’ option<p>&nbsp;</p>No thresholds|The winner is determined by the highest ‘Yes’ vote only
|B4|Vrtotal|2.50%<br>₳1,250,000|Voter Rewards<p>&nbsp;</p>Rewards are received by casting votes
|B5|Artotal|2.50%<br>₳1,250,000|Community Review Rewards<br>LV0 (20% of share)<br>LV1 (80% of share)
|B6|AArtotal|0.40%<br>₳200,000|Community Moderator Rewards<p>&nbsp;</p>LV2 (up to ₳5 ada for each review check)
|B7|Cttotal|0.22%<br>₳110,000<p>&nbsp;</p>₳10,000 per CT<p>&nbsp;</p>30% (₳3,000) Deliverable 1<br>70% (₳7,000) Deliverable 2|Challenge Team rewards paid for:<p>&nbsp;</p>1. Deliverable 1: Introducing the challenge during F10 launch<p>&nbsp;</p>2. Deliverable 2: Onboarding FPs and conducting PoL verification
|B8|Pam|1.20%<br>₳600,000<p>&nbsp;</p>Breakdown:<br>0.40% ₳200,000 for<br>Project < ₳150,000<br>- ₳200 per Milestone PoA<p>&nbsp;</p>0.80% ₳400,000 for<br>Project > ₳150,000<br>- ₳300 per Milestone PoA|Project Accountability Management Rewards<p>&nbsp;</p>Rewarding Community Reviewer help to verify:<br>1. Statement of Milestones (SoM)<br>2. Milestone Proof of Achievement<p>&nbsp;</p>[1] Funded projects will submit to Catalyst a Statement of Milestones<p>&nbsp;</p>SoM is verified by at least 2 community reviewers and rewarded ada for their work.<p>&nbsp;</p>[2] PoA conducted by a reviewer representative. PoA incentive is paid to reviewers.<p>&nbsp;</p>Where proposals are over ₳200,000 reviews must be conducted by 2 separate reviewers.<p>&nbsp;</p>Maximum reward is ₳200/₳300 each for 2 reviewers to carry out PoA.   
|B9|Voter Rewards Formula|Vrj=stakejstaketotalVrtotal|Voter rewards will be given for active participants only in proportion to the voting power voters have.<p>&nbsp;</p>stakej - voter’s stake;<br>staketotal - total amount of ‘active’ stake.
|B10|Community Review  LV0 reward formula|0.5%<br>₳250,000<p>&nbsp;</p>% Share of rewards taken from 20% of the allocated budget<p>&nbsp;</p>Maximum ₳17 per review  
|B11|Community Review LV1 reward formula / $ price per LV1 Community reviewer reward |2%<br>₳1,000,000<p>&nbsp;</p>₳33 per review taken from 80% of the allocated  budget|A simple price paid per review 2% of total budget
|B12|Community Review LV2 (Community Moderators) reward formula / $ per Lv2 reward|0.4%<br>₳200,000<p>&nbsp;</p>Maximum ₳5 per LV2 flagged review check
|B13|# of LV1 reviews that will be rewarded in a round|10-80 Reviews per LV1 Community Reviewer are rewarded under this parameter|A limit to how much an individual LV1 can be rewarded for their allocation in a single funding round.<p>&nbsp;</p>Minimum rewards threshold is ₳330 in ada for 10 reviews. Any number of reviews under this amount will not be rewarded.<p>&nbsp;</p>Any reviews above the threshold allocation number (80) will be included into the LV0 pot
| |Back-End Parameters| | |
|C1|Direct Voting privacy state|Yes|Are votes private?
|C2|Funds under control|50,000,000 ada|Fund will Control 50M ada
|C3|Voting power threshold|450,000,000 lovelace.<br>(450 ada)<p>&nbsp;</p>Communicate threshold as 500 to account for tx fees|Minimal stake threshold to become a voter, based on the efficiency benchmarks of the voting protocol.<p>&nbsp;</p>Specific value of the voting stake threshold will be defined by the protocol benchmarks.<p>&nbsp;</p>Note that threshold must be lowered by 50 ada from the amount stated to the community to address registration fees.
|C4|current_fund_name|Fund10|
|C5|current_insight_sharing_start|Jun 22, 2023|
|C6|current_proposal_submission_start|Jun 22, 2023|
|C7|current_refine_proposals_start|Jun 22, 2023|
|C8|current_finalize_proposals_start|Jul 13, 2023|
|C9|current_proposal_assessment|Jul 20, 2023|
|C10|current_assessment_qa_start|Aug 10, 2023|
|C11|current_snapshot_start|Aug 18, 2023|
|C12|current_voting_start|Aug 31, 2023| 
|C13|current_voting_end|Sep 14, 2023|
|C14|current_tallying_end|Sep 18, 2023|
