# Activity Dates and Times

**Question:** What are the dates and timestamps of when contributor activities occur?

## Overview
This metric focuses on identifying the dates and times when individuals contribute to open-source projects. Analyzing timestamps of contributions can help infer activity patterns and even estimate contributors' geographic regions, especially when direct time zone data is unavailable (e.g., contributions in non-UTC). This information can offer transparency for employers about employee contributions and provide open-source project managers with insights into global engagement and when contributors are most active.

## Want to Know More?

<span markdown="1"><details>
<summary>Click to read more about this metric.</summary>

### Data Collection Strategies
- Timestamps from activities such as commits, issues, pull requests, and mailing list messages should be captured.
- Aggregation of data by UTC or contributors' local time can reveal activity patterns globally.
- Collaboration tools like GitHub, GitLab, and email platforms can provide timestamped activity data.
  
### Filters
- **By Organization:** Contributions can be filtered to focus on specific individuals affiliated with organizations.
- **Aggregation by UTC Time:** Shows global contributions and identifies project active periods.
- **Aggregation by Local Time:** Helps track when contributors contribute during their working hours or off-hours.
- **Repository ID:** Filters data by specific repositories or subprojects.
- **Community Segmentation:** Contributions can be segmented by regions or time zones, such as EU or US activities, to visualize community participation.
  
### Visualizations

![Date Time Chart 1](https://raw.githubusercontent.com/chaoss/wg-metrics-development/main/focus-areas/time/images/activity-dates-and-times_1.png)
*Figure 1: Heatmap showing contribution activity by UTC time across the globe ()*

![Date Time Chart 2](https://raw.githubusercontent.com/chaoss/wg-metrics-development/main/focus-areas/time/images/activity-dates-and-times_2.png)
*Figure 2: Chart displaying when contributors are active based on local times ()*
   
![Date Time Chart 3](https://raw.githubusercontent.com/chaoss/wg-metrics-development/main/focus-areas/time/images/activity-dates-and-times_3.png)
*Figure 3: Global distribution of contributor activities by time zone ()*

![Date Time Chart 4](https://raw.githubusercontent.com/chaoss/wg-metrics-development/main/focus-areas/time/images/activity-dates-and-times_4.png)
*Figure 4: Breakdown of contribution activity by repository segments ()*

</details></span><br>

## References
- **[Coordinated Universal Time (UTC)](https://en.wikipedia.org/wiki/Coordinated_Universal_Time):** Used to standardize timestamps for analyzing contributions across different regions and tools.

## Contributors
- None Specified

## Additional Information
- To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/activity-dates-and-times.md).  
- To reference this metric in software or publications, please use this stable URL: [https://chaoss.community/?p=3444](https://chaoss.community/?p=3444).

<!-- # For groupings in the knowledge base
 Context tags: Contributor Activity, Global Participation 
 Keyword tags: time zone, timestamp, activity, engagement, contributor location, change request, date, issue, time
 -->
