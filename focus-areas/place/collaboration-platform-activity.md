# Collaboration Platform Activity

**Question:** What is the count of activities across digital collaboration platforms (e.g., GitHub, GitLab, Slack, email) used by a project?

## Overview
Open source projects use various digital communication and collaboration platforms such as email, social media, chat applications, and code management technologies like GitHub or GitLab. This metric measures the volume and location of message activity across these platforms, providing insights into where and how collaboration happens in the project.

Understanding where the community interacts helps track engagement, transparency, and project accessibility. This metric is crucial for evaluating communication processes and identifying the most effective channels for community participation.

## Want to Know More?

<span markdown="1"><details>
<summary>Click to read more about this metric.</summary>

### Objectives
The Collaboration Platform Activity metric helps:
- Understand where the community is collaborating and how it communicates.
- Identify the processes followed by each project based on communication logs.
- Demonstrate the level of transparency in project communications.
- Help contributors find the appropriate platform for making contributions and connecting with the project.
- Enable project maintainers to determine the optimal number of communication channels to efficiently share information and engage contributors.
- Identify the lowest-barrier channels for engagement.
- Support other metrics, such as [Burstiness](https://chaoss.community/?p=3447), [Project Velocity](https://chaoss.community/?p=3572), [Activity Dates and Times](https://chaoss.community/?p=3444), and [Chat Platform Inclusivity](https://chaoss.community/?p=3536).

### Data Collection Strategies
The unit of data collection is the individual activity on a platform. Metadata related to this metric can include:
- Timestamp of the activity
- Sender (user or bot)
- Threaded or non-threaded platform type
- Data collection date
- Platform message identifier

### Filters
* Number of people
* Number of messages
* Number of comments on Issues and Change Requests
* Type of channel (mailing list, irc, and so on)
* Activity per day of the week
* [Contribution attributions](https://chaoss.community/metric-contribution-attribution/) (e.g., people or organizations)

### Visualizations
1. **Visualization of Platform Activity:**  
   Display the count of platform activities over time.
   ![GrimoireLab Implementation](https://raw.githubusercontent.com/chaoss/wg-metrics-development/main/focus-areas/place/images/collaboration-platforms.png)  
   *Figure 1: Collaboration platform activity chart (GrimoireLab)*

2. **Interactive Dashboards:**  
   [GrimoireLab Dashboard](https://chaoss.biterg.io/app/kibana#/dashboard/ab68fe20-17f2-11e9-872f-e17019e68d6d)
   *Figure 2: GrimoireLab dashboard displaying platform activity metrics (GrimoireLab)*

</details></span>

## References
- [Related Metric: Chat Platform Inclusivity](https://chaoss.community/?p=3536)
- [Related Metric: Issues New](https://chaoss.community/?p=3634)

## Contributors
- Elizabeth Barron
- Sean Goggins
- Matt Germonprez
- Daniel Izquierdo
- Dawn Foster
- Beth Hancock
- Kevin Lumbard
- Vinod Ahuja
- Yigakpoa L. Samuel (Ikpae)

## Additional Information
- To edit this metric please submit a Change Request here: https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/place/collaboration-platform-activity.md
- To reference this metric in software or publications please use this stable URL: https://chaoss.community/?p=3484

<!-- # For groupings in the knowledge base
 Context tags: Collaboration Platform, Chat platform, Platform Activity
 Keyword tags: GitHub, GitLab, IRC, Slack, Email, place, where
 →
