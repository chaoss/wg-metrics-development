# Time to Close

**Question: How much time passes between creating and closing an operation such as an issue, change request, or support ticket?**

## Overview

Time to Close measures the duration between the creation and closure of operations such as issues, change requests, or support tickets. The operation needs to have an open and closed state, as is often the case in code review processes, question and answer forums, and ticketing systems; a related metric includes [Issue Resolution Duration](https://chaoss.community/metric-issue-resolution-duration/). Data points are calculated by subtracting the creation date from the closure date for each completed operation.
Time to Close helps determine how responsive a community is, which can aid efforts to be inclusive, attract, retain new and existing contributors. It also helps identify characteristics of operations that affect the speed of closure, such as finding best practices, identifying areas for improvement, and assessing efficiency. It can help identify biases in timely responses to different community members, detect changes in community activity (like maintainer burnout or reduced diversity of contributions).

## Want to Know More?

<span markdown="1"><details>

<summary>Click to read more about this metric.</summary> 

### Data Collection Strategies

The time to close metric may be contextual based on the project activity and objectives. For example, the time to close a bug report may provide different information than the time to close a new feature request. Data collection strategies should address different project objectives. Other variables that may influence these processes are:

*   Issue Tracking Systems: the type of issue such as bug report, blueprint (OpenStack nomenclature), user story, feature request, epic, and others may influence how long this event takes to be closed. Other variables, such as the priority or severity may help to advance how quickly this event will be closed.
*   Change Request Processes: this depends on the change request infrastructure, as Gerrit, GitHub or mailing lists (as in the Linux Kernel) and may differ depending on how complicated the process is. For example, newcomers or advanced and experienced developers will proceed in different ways and with more or less time required.
*   Question and Answer Forum: this depends on the quality of the answer and the opinion of the person asking the question. A valid answer is marked, and the process is closed once the person questioning has successfully found a correct answer to their question.

### Filters

*   Creator of operation (e.g., new contributor vs. maintainer)
*   First closed, final closed
*   Labels (e.g., bug vs. new feature)
*   Change Request Merge Status (e.g. Time to Merge or Time to Close without Merge)

### Visualizations

GrimoureLab
![Average and median time to close an Issue from GrimoireLab](https://raw.githubusercontent.com/chaoss/wg-common/main/focus-areas/time/images/time-to-close_1.png)

</details></span>

## References

*   [Pull Requests Efficiency](https://chaoss.github.io/grimoirelab-sigils/panels/github-pullrequests-efficiency/)
*   [Issues Efficiency](https://chaoss.github.io/grimoirelab-sigils/panels/github-issues-efficiency/)
*   [Efficiency:TimingOverview](https://chaoss.github.io/grimoirelab-sigils/panels/efficiency-timing-overview/)
*   “Practice P.12: Respond to all submissions” from “Appendix to: Managing Episodic Volunteers in Free/Libre/Open Source Software Communities” by Ann Barcomb, Klaas-Jan Stol, Brian Fitzgerald and Dirk Riehle: https://opus4.kobv.de/opus4-fau/frontdoor/index/index/docId/13519

## Contributors

*   Matt Germonprez

*   Kevin Lumbard

*   Peculiar C. Umeh

## Additional Information

To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-common/blob/main/focus-areas/time/time-to-close.md)

To reference this metric in software or publications please use this stable URL: [ https://chaoss.community/?p=3446](https://chaoss.community/?p=3446)

<!-- # For groupings in the knowledge base
Context tags: Lifecycle, Contribution
Keyword tags: time, issue, change request, activity
-→ 
