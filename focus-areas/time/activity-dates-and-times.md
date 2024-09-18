# **Activity Dates and Times**

**Question:** What are the dates and timestamps of when contributor activities occur?

## **Overview**
This metric focuses on identifying the dates and times when individuals contribute to open-source projects. Analyzing timestamps of contributions can help infer activity patterns and even estimate contributors' geographic regions, especially when direct time zone data is unavailable (e.g., contributions in non-UTC). This information can offer transparency for employers about employee contributions and provide open-source project managers with insights into global engagement and when contributors are most active.

## **Want to Know More?**

<span markdown="1"><details>
<summary>Click to read more about this metric.</summary>

### **Data Collection Strategies**
- Timestamps from activities such as commits, issues, pull requests, and mailing list messages should be captured.
- Aggregation of data by UTC or contributors' local time can reveal activity patterns globally.
- Collaboration tools like GitHub, GitLab, and email platforms can provide timestamped activity data.
  
### **Filters**
- **By Organization:** Contributions can be filtered to focus on specific individuals affiliated with organizations.
- **Aggregation by UTC Time:** Shows global contributions and identifies project active periods.
- **Aggregation by Local Time:** Helps track when contributors contribute during their working hours or off-hours.
- **Repository ID:** Filters data by specific repositories or subprojects.
- **Community Segmentation:** Contributions can be segmented by regions or time zones, such as EU or US activities, to visualize community participation.
  
### **Visualizations**

1. **Heatmap of Global Activity by UTC Time:**
   ![IMG_5315](https://github.com/user-attachments/assets/570be6eb-547e-4490-86b3-4cfa8c74006e)
   *Figure 1: Heatmap showing contribution activity by UTC time across the globe (Source, Year)*

2. **Contribution Activity by Local Time:**
   ![IMG_5316](https://github.com/user-attachments/assets/949a0e83-c027-4c57-873d-1e2192694bcb)
   *Figure 2: Chart displaying when contributors are active based on local times (Source, Year)*

3. **Distribution of Contributions by Time Zones:**
   ![IMG_5317](https://github.com/user-attachments/assets/0974b5bf-75b9-4ef7-b62f-f8b3cdb858fb)
   *Figure 3: Global distribution of contributor activities by time zone (Source, Year)*

4. **Repository-Specific Activity Patterns:**
   ![IMG_5318](https://github.com/user-attachments/assets/458adcc6-080f-499b-b041-88e62105935a)
   *Figure 4: Breakdown of contribution activity by repository segments (Source, Year)*

</details></span>

## **References**
- **[Coordinated Universal Time (UTC)](https://en.wikipedia.org/wiki/Coordinated_Universal_Time):** Used to standardize timestamps for analyzing contributions across different regions and tools.

## **Contributors**
- None Specified

## **Additional Information**
- To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-common/blob/main/focus-areas/time/activity-dates-and-times.md).  
- To reference this metric in software or publications, please use this stable URL: [https://chaoss.community/?p=3444](https://chaoss.community/?p=3444).

<!-- # For groupings in the knowledge base
 Context tags: Contributor Activity, Global Participation 
 Keyword tags: time zone, timestamp, activity, engagement, contributor location, change request, date, issue, time
 →
