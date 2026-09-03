# Case 4 : GameOn

## Solution to Designing and Building a Prototype: Designing a referral program to drive growth at GameOn

### Context & Core Problem

- **The Goal:** GameOn (a casual gaming app with 20M registered users and 1.5M DAUs) faces a funding crunch and high paid user acquisition costs ($2.50 per acquisition). The objective is to redesign the referral program to lower costs, boost organic growth, and improve user retention.
- **The Opportunity:** GameOn’s current referral performance is weak due to low participation (12%), a modest conversion rate (2.4%), and an uninspiring reward system (small virtual currency grants).

### As a product manager on the team, I need to answer the following questions:

**1. What is “successful referrals” a function of? Can you write it as a set of product outcomes?**

**i Mathematical Function & Product Outcomes**

  Successful Referrals ($R_{success}$) can be broken down into a standard viral funnel formula:

  $$R_{success} = N \times P \times S \times C \times E$$
  
  - $N$ (Active User Base): Number of Daily/Monthly Active Users.
  
  - $P$ (Participation Rate): $\%$ of active users who open/engage with the referral feature.
  
  - $S$ (Shares per Participant): Average number of referral invites sent per active referrer.
  
  - $C$ (Conversion Rate): $\%$ of invited users who download, install, and complete onboarding.
  
  - $E$ (Engagement & Retention Rate): $\%$ of referred users who hit a meaningful activation milestone (e.g., play $X$ games or reach Level $Y$).

**ii Product Outcomes Set**

**1. Increase Referral Discovery & Triggering ($P$):** Move participation rate from **12%** to **25%** by integrating contextual in-game triggers.  

**2. Increase Sharing Velocity ($S$):** Increase invites per user from 1.1 to 3+ by leveraging frictionless social channels (WhatsApp, direct deep links).  

**3. Boost Invite-to-Install Conversion ($C$):** Elevate conversion from **2.4%** to **6%+** via personalized landing screens and double-sided, high-value incentives.  

**4. Drive High-Quality User Activation ($E$):** Ensure new users reach "Day 1 Activation" (e.g., playing 3 casual matches) rather than just downloading and abandoning the app.

**2. Which product outcomes would you focus on?**

**i Focus Product Outcomes**

Given GameOn’s funding crunch and goal to lower the **$2.50 CAC** via organic acquisition, the primary focus should be on:

**Priority 1: Referral Participation Rate ($P$) — Currently 12%**

- **Why:** 88% of active users aren't participating because the program lacks excitement and visibility. Fixing the top-of-funnel trigger yields immediate leverage without extra acquisition spending.

**Priority 2: Invite Conversion Rate ($C$) — Currently 2.4%**

- **Why:** A 2.4% conversion rate indicates friction at the recipient's end. The current "small amount of virtual currency" isn't a compelling reason for a friend to download the app.

**Priority 3: Post-Referral Activation ($E$)**

- **Why:** To ensure GameOn acquires high-quality users rather than incentive-gaming bots, rewards must be tied to active gameplay, directly addressing the **35% D30 retention rate**.

**3. What are the potential opportunities to achieve the desired product outcomes?**

**i Potential Opportunities**

| Funnel Stage | Identified Opportunity | Key Metric Impacted |
| --- | --- | --- |
|**Trigger & Discovery** | Shift from a hidden "Settings menu link" to emotional "Peak Joy" moments (e.g., winning a tournament, unlocking a high score). | Participation Rate ($P$) |
|**Incentive Alignment** | Replace flat, low-value virtual currency with milestone-based, exclusive rewards (skins, ad-free passes, power-up bundles). | Participation ($P$) & Conversion ($C$) |
| **Social Friction**    | Implement 1-click sharing via WhatsApp and Instagram DMs with prepopulated dynamic preview cards showing the friend's game stats. | Share Rate ($S$) |
| **Onboarding & Landing** | Use deferred deep-linking so referred users land directly in a co-op match or private lobby with their friend. | Conversion Rate ($C$) |

**4. What are the ideas you can think of to improve the referral program?**

**i Strategic Growth Ideas**

Following Andrew Chen’s growth principles—focusing on double-sided loops, social proof, and contextual placement—here are core product concepts:

**Idea 1: "Buddy Clash" Private Lobbies (Co-op Driven Viral Loop)**

- **Mechanism:** Allow existing users to challenge friends to a 1v1 match or co-op puzzle via WhatsApp. The recipient gets a direct link that opens a "guest match" or instant game preview.

- **Incentive:** Both players earn a **2x XP Boost** and **Exclusive Avatar Frames** upon completing their first 3 matches together.  

- **Why it works:** Leverages game mechanics rather than transactional cash, driving high engagement ($E$) and high quality.

**Idea 2: Tiered & Milestone Reward Ladder ("Streak Referrals")**

- **Mechanism:** Move away from flat rewards. Introduce a visual progress bar:
  
  - _1 Referral:_ 500 Coins + 3 Power-ups
  - _3 Referrals:_ 3 Days of Ad-Free Premium Pass
  - _5 Referrals:_ Exclusive Limited-Edition Character/Skin (Social flex)
  
- **Why it works:** Gamifies the referral process for the referrer, driving higher share density per user ($S$).

**Idea 3: Smart Contextual Triggers ("Victory Share")**

- **Mechanism:** Trigger referral prompts only during high-dopamine moments:

  - Immediately after a user sets a new personal high score.
  - After receiving a daily login streak bonus.
  - Prompt wording: "_You're on a 5-game winning streak! Gift a 1-Day Pass to a friend to join your squad._"
    
- **Why it works:** Increases participation ($P$) by capitalizing on user satisfaction.

**Idea 4: Dynamic & Personalized Recipient Landing**

- **Mechanism:** When the recipient clicks the link, the App Store / First-Open screen displays:

  "_[Friend's Name] sent you 500 Coins & challenged you to a Puzzle Duel!_"

- **Why it works:** Provides immediate social proof and context, reducing drop-offs between download and registration to boost conversion ($C$).

## Go back to [README](README.md)
