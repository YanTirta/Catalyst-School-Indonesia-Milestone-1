# **Community Review - Score weight**

>A score weighting will be applied to all reviews submitted beyond the reviewer’s allocation.

In past funds, the score for each criterion was calculated with the simple average of all the valid reviews. Still, this approach leaves the door open for attacks on score ratings since a bad actor could feasibly create an unlimited number of LV0 accounts and significantly influence the final score.

To prevent this, each criterion's score is calculated differently by weighting the allocated reviews versus the non-allocated reviews. Allocated reviews are weighted 80/20 against non-allocated reviews.  

**Reviews by LV0 and LV1 are not treated differently in the voting app interface;** it is only the weighted score that differs, which impacts the final aggregated score rating of reviews. The last rating for each criteria calculation is protected against spam attacks by giving more weight to allocated reviews.

**Implementation:**

<img width="669" alt="Community Review - Score Weight 1" src="https://github.com/user-attachments/assets/8a457e09-e4ef-4654-be99-aaef852f4399">
<img width="670" alt="Community Review - Score Weight 2" src="https://github.com/user-attachments/assets/f9df56e7-6a00-4bfc-858f-d47a0e078c7e">
<img width="669" alt="Community Review - Score Weight 1" src="https://github.com/user-attachments/assets/8a457e09-e4ef-4654-be99-aaef852f4399">
<img width="673" alt="Community Review - Score Weight 3" src="https://github.com/user-attachments/assets/f01cfcc4-3ce2-4d71-b6ec-7f26f530e7a6">
