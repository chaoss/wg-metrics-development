# Burstiness

**Question:** How are short timeframes of intense activity, followed by a corresponding return to a typical pattern of activity, observed in a project?

## Overview

Burstiness measures the number of reasons that may prompt a sudden increase or decrease in the amount of activity within a repository. Data points are calculated by analyzing the fluctuations in activity metrics such as issues, merge requests, commits, or comments. Examples of root causes for bursts in activity include:release cycles, global pandemics, hackathon activities, mentorship programs, Conferences, meetups, and other events where tools are presented, conventional and social media announcements and mentions, critical bugs as raising awareness and getting people’s attention, community design meetings or brainstorming meetings to address a particular issue, and community members show up from another community that is relying on your project (e.g., dependencies). Burstiness hepls also measure the impact of influential external activities and  differentiate skewed activity versus normal activity. Understanding the underlying reasons for bursts can inform decision-making, resource allocation, and community engagement strategies.

## Want to Know More?

<span markdown="1"><details>

<summary>Click to read more about this metric.</summary>

### Data Collection Strategies

*   Quantitative
    *   Time box activities identifying deviations away from some norm
    *   Outliers for certain thresholds, using statistics like Bollinger Bands to measure stability or volatility: https://en.wikipedia.org/wiki/Bollinger\_Bands

*   Qualitative Interview Questions
    *   Why do you contribute more during a period of time?
    *   What do you believe to be the root cause for particular bursts?
    *   What impact do different events (e.g., hackathons, mentorship program, or conferences) have on project activity?

### Filters

*   Stars
*   Forks
*   Issues or bug reports
*   Labels
*   Downloads
*   Release Tags
*   Change Requests
*   Mail List Traffic
*   Documentation additions or revisions
*   New Repositories
*   Feature Requests
*   Messaging Conversations
*   Conventional and Social Media Activity
*   Conference Attendance and Submissions

### Visualizations

Augur:

![Augur Burstiness](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/images/burstiness_augur.png)

GrimoireLab:

![GrimoireLab Burstiness](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/images/burstiness_augur.png)

</details></span><br>

## References

*   This metric was inspired by the work of Goh and Barabasi (2008): https://arxiv.org/pdf/physics/0610233.pdf

## Contributors

*   Matt Germonprez
*   Kevin Lumbard
*   Peculiar C. Umeh

## Additional Information

To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/burstiness.md)

To reference this metric in software or publications please use this stable URL: [ https://chaoss.community/?p=3447](https://chaoss.community/?p=3447)

<!-- # For groupings in the knowledge base
Context tags: Lifecycle, Contribution
Keyword tags: date, time, activity, cycle
-->
