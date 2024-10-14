# Change Request Review Duration

## Question: How long does it take a [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) reviewer to review a specific change request?

## Overview

Change Request Review Duration measures the average time between a change request submission [review cycle](https://chaoss.community/metric-review-cycle-duration-within-a-change-request) and the time for a first review. This metric measures one review, however, there may be multiple reviews within a [Review Cycle Duration within a Change Request](https://chaoss.community/metric-review-cycle-duration-within-a-change-request) and this measures the time of each review.  The time waiting for a review is zero if the change request is merged without any requested revisions or clarification. Low change request review duration indicates an active community with engaged reviewers, timely feedback for improving code quality and faster project progress. High change request review duration may signal overburdened reviewers, lack of expertise, or hesitation to approve changes which can lead to contributors' frustrations or increased technical debt. Analyzing change request review duration across different contributors can reveal disparities in review times, maintainer workload adequacy and potential for burnout, whether delays are the responsibility of a reviewer, and discrepancies in review times for different contributors to indicate whether the review process is inclusive.

## Want to Know More?

<span markdown="1"><details>

<summary>Click to read more about this metric.</summary>

### Filters

*   Change Request Review Duration can be filtered by:
*   Reviewer (e.g., name or id)
*   Reviewer role (e.g., maintainer, reviewer, and member)
*   Bot reviews
*   Date and time the [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) was submitted or modified
*   Date and time of the response
*   [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) type and size may affect the response time.

### Visualization

![Augur Image](https://github.com/chaoss/wg-common/blob/main/focus-areas/time/images/change-request-review-duration_img1.png)

</details></span>

## References

*   [Code Review Decision Fatigue](https://tylercipriani.com/blog/2022/03/12/code-review-procrastination-and-clarity/)
*   [Augur Documentation](https://oss-augur.readthedocs.io/en/main/rest-api/api.html#operation/Mean%20Response%20Times%20for%20Closed%20Pull%20Requests)

## Contributors

*   Vinod Ahuja
*   Dawn Foster
*   Elizabeth Barron
*   Kevin Lumbard
*   Matt Germonprez
*   Sean Goggins
*   Peculiar C Umeh

## Additional Information

To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-common/blob/main/focus-areas/time/change-request-review-duration.md)

To reference this metric in software or publications please use this stable URL:<https://chaoss.community/?p=4920>

<!-- # For groupings in the knowledge base
Context tags: Contribution, Lifecycle
Keyword tags: Change Request Review, Change Request, Code Review, Time, Pull Request
-→
