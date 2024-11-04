# Review Cycle Duration within a Change Request

**Question:** What is the duration of a review cycle within a single change request?

## Overview
Review Cycle Duration measures the time taken for one complete review cycle within a change request. A review cycle starts when a change request is submitted or updated and ends either with an acceptance, rejection, or further requested changes. This metric helps maintainers assess the efficiency of the code review process, identifying potential bottlenecks and areas where delays occur. Understanding the duration of these cycles provides insight into the effectiveness of review practices and the overall workflow of contributions within a project. Characteristics of reviews that have different cyclic pattern lengths. Abandoned or semi-abandoned processes in the review cycles, where either the maintainer or the submitter is slow in responding.

Monitoring this metric allows for identifying trends such as increased review cycle lengths due to complex contributions or delays in reviewer responses, which can impact the project's health and contributor engagement.

## Want to Know More?

<span markdown="1"><details>
<summary>Click to read more about this metric.</summary>

### Data Collection Strategies

Review Cycle Duration is measured as the time length of one review cycle within a single change request.
The duration can be calculated between:
- The moment when each review cycle begins, defined as the point in time when a change request is submitted or updated.
- The moment when each review cycle ends, either because the change request was updated and needs a new review or because it was accepted or rejected.

To calculate Review Cycle Duration, the following data points are collected:
- **Start of review cycle:** Timestamp when a change request is submitted or updated.
- **End of review cycle:** Timestamp when the change request is updated, accepted, or rejected.
- **Review feedback:** Record of interactions, including comments and change requests.
  
This data can be collected from version control systems like GitHub or GitLab.

### Filters

Average or Median Duration, optionally filtered or grouped by:
- Number of people involved in review
- Number of comments in review
- Edits made to a change request
- Project or program
- Organization making the change request
- Time the change request was submitted
- Developers who contributed to a change request
- Change request
- Number of review cycle on a change request (e.g., filter by first, second, …  round)
  
### Visualizations
- None specified

</details></span><br>

## References
- Example of data for developing this metric: [Wikimedia Gerrit Change Request Example](https://gerrit.wikimedia.org/r/c/mediawiki/core/+/194071)

## Contributors
- None specified

## Additional Information
- To edit this metric, please submit a Change Request here: [https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/review-cycle-duration-within-a-change-request.md](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/review-cycle-duration-within-a-change-request.md)
-  To reference this metric in software or publications please use this stable URL: https://chaoss.community/?p=3445

<!-- # For groupings in the knowledge base
Context tags: Code Review Process, Change Requests, Review Cycle Efficiency
Keyword tags: Code Review, Change Request Submissions
-->
