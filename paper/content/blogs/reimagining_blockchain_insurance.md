---
title: "Reimagining an affordable Blockchain-based Insurance"
date: 2020-10-05
weight: 7
slug: "blockchain-insurance"
keywords: ['Blockchain']
toc: true
TocOpen: false
draft: false
hidemeta: false
disableShare: false
tags: ["Decision Making", "Insurance", "Blockchain"]
author: "Andrew Siah"
---

# Insurance 

## Origin of Insurance

You’re a sailor in 17th century Great Britain. Sailing the 7 seas for gold, gospel, and glory. Yet with all the treasures and adventure of sailing, it came with significant risks. With pirates lurking around for booties, lousy hygiene on board, terrible treatment to most sailors, unpredictable storms, and little to no healthcare on board, it’s not far-fetch to say a significant amount of sailors don’t return alive. It pays well, but it probably might cost you your life.

So, you’re willing to take the risk. Good for you. How do you appease your spouse or family that were something to happen to you, the sole breadwinner of the family, that they won’t starve to death? If only there was a way to pool some money with your fellow sailors, and if any of you – unfortunately – do not return, a chunk of the pool would be given to eyour dependants. Thus easing them in giving you their blessing to depart. Aha!

One of the significant insurance milestones came in the 17th century, initiated by the [Lloyd’s of London](https://www.britannica.com/money/topic/insurance/Historical-development-of-insurance). So it began in a coffeehouse in London (duh), where sailors would buy contracts from insurance underwriters for a small sum. In return, you get a piece of agreement, which states that were you to not return in one piece, your family would receive x dollar. Paying a small fee to ensure that the worst-case – your death – is covered was widely accepted and gradually grew beyond just for sailors but for all ventures that involve risk, including:

- Lost cargo due to sinking
- Theft
- Severe illness and the resulting medical expenses
- Fire damage to property and machinery
- Damage to personal belongings during travel

As long as (1) there is a risk for damages or losses (2) it’s a risk that is commonly experienced by others, you can get an insurance policy for it.

Fundamentally, insurance underwriters act as an escrow service (dfn: a bond, deed, or other document kept in the custody of a third party and taking effect only when a specified condition has been fulfilled.) Holding and guarding the pool of money, and guaranteeing that if bad luck befalls you, they will pay you.


## How are Insurance Policies Charged?

Tracing back to the origin of insurance policies. We can split the cost breakdown to,

1. The money that goes into the claim pool (~90%)
2. The fees paid to the handlers for their work in collecting and managing the insurance policies. (~10%)
Yet, as time evolved, the insurance policies we see nowadays include a lot of other costs, including

1. Commission for agents (~30% of total fees)
2. Paying adjustors to prevent mal claims
3. Shareholder profits
4. Wine and dine costs to woo agents so that they’ll give more business to certain insurance companies (as policy buyers tend to be very loyal to their agents, which gives the agents a pretty big say in which company to give their business to)
5. Investment fees, where they take your insurance capitals to reinvest and earn a profit on
6. Actuarists to ensure the company is not overleveraged or underleveraged
7. Management teams to continually refine their policy offerings to ensure it is competitive to policy buyers

All these cause insurance nowadays to be significantly bureaucratic and inefficient compared to how it was initially conceived. Can we think of a way to return to the lean paradigm of insurance?

# Blockchain Insurance

## Enter Blockchain and Smart Contracts

If you’ve been following the buzz on bitcoins, ethereum, and cryptocurrencies, you’ll know that it’s gaining in popularity and adoption in recent years. But what is it under the hood? I want to focus mainly on Ethereum and write decentralized apps (dapps for short). It’s a

1. **Decentralized:** (dfn: no middle man; unlike your insurance companies, and governments, and banks, etc.)
2. **Peer-to-peer:** (dfn: everyone is involved in maintaining and upholding the system; unlike the status quo where only one party maintains the system)
3. **Computerized:** (dfn: something that stores data: who has what insurance policy, who made claims, etc. and processes those transactions: who made a claim, how much is left in the pool after this claim is made, should this claim be allowed to go through)

Enter smart contracts. A common metaphor for smart contracts is to imagine it as a vending machine. A vending machine has its operations and functions all hardcoded into it, such that when

1. You pay $2 into it, and press the coke bottle (that costs $1.50). It will output the coke bottle to you, refund you the money, and log in to its system that it has one less coke
2. You pay $1 into it. It shows that it has received $1 and only lights up the products that cost $1 (Bottle of water).
3. You press the refund button, it will output the money you inserted back to you. All these do not require fees, neither does it require anyone to manage the system because its operations are hard-coded right into its functions.

Imagine if we can get rid of outdated and unnecessary insurance intermediaries (agents, etc.) and if all insurance policies are now smart contracts. Example being,

- You bought a fire policy for your house. (Replacing agents)
- Your house got caught on fire, sadly.
- There is a police report that proves that there was no malintent nor foul play in the fire (Replacing the role of the adjuster) Upon receiving the above inputs, the smart contract automatically calculates the damage you deserve and transfers the sum to you from the claim pool. (Replacing insurance companies)
- It then readjusts the general insurance fees regularly based on the sum remaining in the claim pool and the number of claims this year. (Replacing the role of the actuaries)

## Comparative Benefits

1. **Cheaper insurance policies**

Today, a large part of insurance costs goes to paying unnecessary functions that do not serve the bottom line of claimants and policy-buyers. Smart contracts replace these functions and don’t cost any labor (except for computational resources).

2. **Immutable decision-makings**

Present insurance claiming process is actually quite subjective. If your agent is of high standing and has a significant client base, they can influence the companies to allow specific dubious claims to pass through. At the end of the day, the company never loses (neither does the shareholders); the costs are passed down to every single policyholder, thus making your policy fee more expensive. [1] A smart contract-based insurance model would be fair and unbiased, thus ensuring every policy holder’s minimum costs.

3. **Speed up claim processing**

The present model requires going through multiple hoops to claim (The adjustor process alone could take months at times if your claims are significant). With smart contracts, all the red taped is reduced to conditional statements. Thus eliminating all the processing hoops as well.

# Going Forth

## Challenges before reaching Insurance-Utopia

1. **Complexity of policies**

A smart contract is limited to conditional statements. Insurance policies are filled with complicated terms and conditions to prevent exploitation. [2] So it would take some time to hard-code these insurance policies to optimize for minimum costs and maximum satisfaction and coverage for policy-buyers. Let’s be clear, blockchain insurance is not here to replace and destroy current insurance companies; they’re here to revolutionize and complement one another.

2. **Government Regulation**

Current insurance companies are insured (irony) by the central bank. [3] A decentralized smart-contract system is more challenging for governments to regulate and thus would be rather hard to be guaranteed by centralized entities. At the end of the day, the blockchain insurance would require trust in the system and contract alone, necessitating open-sourcing the code-based for public scrutiny and improvement.

# How Do We Get There?

I propose building a decentralized insurance app on a private blockchain with simulated actors to test run the system against. And organizing regular competitions whereby we invite people to contribute, scrutinize and build upon the system. Once it becomes more stable and grows in adoption, we can launch versions of it onto the public blockchain (such as what uniswap has done for decentralized exchange). And start deploying it and making the world more insured and enable people to truly live without fear.

----

[1] This is like how cheaters spoil public goods (and insurance functions like a public good). If a person cheats or chooses not to bear the costs of the public good but still partakes in its benefit, the cost is passed on to the rest.

[2] Yet every single T&C comes with the trade-off of increased complexity, which increases distrust of insurance companies. Agents give off the facade that this complexity is comprehensible but at the costs of 30% of your fees.

[3] Double irony in that insurance firms actually buys insurance policies from other companies for their own policies, so on and so forth.

[4] Suggestion to build a simulation of algorithms, whereby we invite people to hack and exploit the system to make the best insurance algorithm and contract.