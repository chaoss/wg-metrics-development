# Collaboration Platform Activity

Question: What is the count of activities across digital collaboration platforms (e.g., GitHub, GitLab Slack, email) used by a project?

## Description
Open source projects use many different digital communication and collaboration platforms. These platforms may include email, social media, chat applications, and code management technologies (e.g., GitHub, GitLab). This metric is a measure of where and how much message activity is occurring across collaboration platforms.

## Objectives
The objective of the Collaboration Platform Activity metric is to understand where the community is collaborating. This metric can help: 
- To develop insights related to the processes followed by each project, which are more likely to be accurate if our review of the communication logs is as complete as possible.
- Demonstrate how open and transparent a project is.
- People find the appropriate place to make contributions and connect with the project.
- Project maintainers determine the optimal number of channels to effectively and efficiently share information while allowing contributors to connect in the way that works best for them
- Find the lowest barrier channels for engagement
- Inform other metrics like: [Burstiness](https://chaoss.community/metric-burstiness/), [Project Velocity](https://chaoss.community/metric-project-velocity/), [Social Listening](https://chaoss.community/metric-social-listening), [Activity Dates and Times](https://chaoss.community/metric-activity-dates-and-times/), [Chat Platform Inclusivity](https://github.com/chaoss/wg-diversity-inclusion/issues/318)

## Implementation

The unit of data collection is the individual activity on a platform. Metadata related to the metric can include:
* Timestamp
* Sender
* Threaded/Non-Threaded Platform
* Data Collection Date
* Platform message identifier

### Filters
* Number of people
* Number of messages
* Number of comments on Issues and Change Requests
* Type of channel (mailing list, irc, and so on)
* Activity per day of the week
* [Contribution attributions](https://chaoss.community/metric-contribution-attribution/) (e.g., people or organizations)

### Visualizations

![GrimoireLab Implementation](https://raw.githubusercontent.com/chaoss/wg-common/main/focus-areas/place/images/collaboration-platforms.png)

https://chaoss.biterg.io/app/kibana#/dashboard/ab68fe20-17f2-11e9-872f-e17019e68d6d

### Tools Providing the Metric
* Orbit.love is a community management platform that captures this for a few channels: https://docs.orbit.love/docs/adding-activities
* GrimoireLab
* Augur

## References
* Related metric: https://chaoss.community/metric-chat-platform-inclusivity/
* Related metric: https://chaoss.community/metric-issues-new/

## Contributors
* Elizabeth Barron
* Sean Goggins
* Matt Germonprez
* Danial Izquierdo
* Dawn Foster
* Beth Hancock
* Kevin Lumbard
* Vinod Ahuja 

*The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other law. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md) for additional guidance.*

