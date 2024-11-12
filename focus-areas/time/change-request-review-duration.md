# Change Request Review Duration

### This metric is a release candidate. To comment on this metric please see Issue [#88](https://github.com/chaoss/wg-common/issues/88). Following a comment period, this metric will be included in the next regular release.

**Question: How long does it take a [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) reviewer to review a specific change request?**

## Overview

The change request review duration metric measures the average time between a change request submission and the time for a first [review](https://chaoss.community/metric-review-cycle-duration-within-a-change-request/). Low [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) review duration indicates an active community with engaged reviewers, active contributors and members, timely feedback for improved code quality and faster project progress. High change request review duration may signal overburdened reviewers, lack of expertise, or hesitation to approve changes. This can lead to contributors frustration: delayed reviews discourage contributions and may lead to outdated changes. or increased technical debt: delays can cause code to diverge from the codebase, making future integration challenging. Analyzing change request review duration across different contributors can reveal disparities in review times, potentially indicating factors responsible. By addressing these disparities, communities and projects can create a more inclusive and equitable environment.

## Want to Know More?

<span markdown="1"><details>

<summary>Click to read more about this metric.</summary>

### Data Collection Strategies

*   Survey project contributors.
*   Use a survey to gather project demographics. (For example, using the Open Demographics questions)
*   Survey new community members as identified through such ways as attending newcomer hangout, recent introductions, and time to first
    PR mrge.
*   Survey that is activated by certain types of contributions like non-code contribution, community engagement etc.

### Filters

*   Change Request Review Duration can be filtered by:
*   Reviewer (e.g., name or id)
*   Reviewer role (e.g., maintainer, reviewer, and member)
*   Bot reviews
*   Date and time the [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) was submitted or modified
*   Date and time of the response
*   [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) type and size may affect the response time.

### Visualizations

![Augur Image](https://github.com/chaoss/wg-common/blob/main/focus-areas/time/images/change-request-review-duration_img1.png)

</details></span>

## References

*   [Augur](https://augurlabs.io/)
*   [GrimoireLab](https://chaoss.github.io/grimoirelab/)
*   [Code Review Decision Fatigue](https://tylercipriani.com/blog/2022/03/12/code-review-procrastination-and-clarity/)
*   [Augur Image API](http://augur.chaoss.io/api/unstable/pull_request_reports/mean_response_times_for_PR?repo_id=25440)
*   [Documentation](https://oss-augur.readthedocs.io/en/main/rest-api/api.html#operation/Mean%20Response%20Times%20for%20Closed%20Pull%20Requests)
*   [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md)

## Contributors

*   Vinod Ahuja
*   Dawn Foster
*   Elizabeth Barron
*   Kevin Lumbard
*   Matt Germonprez
*   Sean Goggins

## Additional Information

To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/issue-resolution/issue-resolution-duration.md).
To reference this metric in software or publications please use this stable URL: <https://chaoss.community/?p=3630>

<!-- # For groupings in the knowledge base
Context tags: Contribution, Lifecycle
Keyword tags: Change Request Review, Change Request, Code Review, Time, Pull Request
-->
