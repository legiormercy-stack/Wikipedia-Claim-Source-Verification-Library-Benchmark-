# Overview
This purpose of this task is to create a dataset of manually verified claims that could act as a gold-standard benchmark for the Wikipedia Claim Source Verification Library. All the claims in this dataset will be gotten from Wikipedia articles and the data set will be written using JSON schema. This task is important because it is imperative that claims are properly verified to avoid misinformation and to also readily identify ghost references made by AI bots. This dataset could also potentially become a guide to students, researchers or others looking to verify claims.

## Definition of Terms
1. **Claim ID:** This is the identification number assigned to each claim. The claims will be arranged in chronological order, from first to last.
2. **Claim:** This is the proposition to be verified.
3. **Article:** This is the title of the Wikipedia article.
4. **Source:** This is the title of the article cited.
5. **Source link:** This is the link to the cited article.
6. **Verdict:** This is measures if the source supports the claim or not. It can either be; Supported, Partially Supported or Not Supported.
7. **Remark:** This is a brief explanation on why you came to your verdict.
8. **Status:** This is the final status of the claim verified. It can either be; Verified, Not Verified, or Inconclusive.

To get more information on how the task should be carried out or how to decide which labels to use, kindly read the <a href="(https://github.com/legiormercy-stack/Wikipedia-Claim-Source-Verification-Library-Benchmark-/blob/main/docs/claim-verification-guidelines.md)">claim verification guidelines.</a>


## Data Structure 
