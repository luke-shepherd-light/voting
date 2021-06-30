# Proportional Representation by Multiple Fractional Transferable Votes

This voting scheme is a hybrid of

    Proportional Representation by Single Transferable Vote,
    Open List Voting and
    Approval Range Voting.


Each voter can express multiple first preferences, multiple second preferences and so on, and there can be gaps e.g. no third preference, followed by several fourth or fifth preferences.

Preferences must be expressed as whole positive numbers or will be ignored (treated as zero). A value of 1000 indicates a first preference. Any value higher than 1000 is treated as 1000. A value of 999 indicates a second preference. 

Each candidate on the list is either an individual or a sub-list. When selecting a sub-list there is a sub-vote to indicate preferences within the list. Sub-lists may contain further sub-lists. 

A ballot with multiple first (or highest) preferences is split into sub-ballots with fractional weights.

The initial votes for each candidate is the sum of the weighted ballots in which that candidate is the highest preference.

The approval value for each candidate is the weighted sum of the preferences.

The initial quota for election is calculated as a fraction (number of ballots) / (1 + number of seats).

If an individual candidate achieves greater than the quota then their surplus is a fraction of all their ballots. A list candidate can achieve one or more quotas and their surplus is not transferred until the last seat is being filled (unless the list is equal in size to the number of quotas already achieved). 
