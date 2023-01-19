# Change Request Review Duration
### This metric is a release candidate. To comment on this metric please see Issue [#88](https://github.com/chaoss/wg-common/issues/88). Following a comment period, this metric will be included in the next regular release.

## Question: How long does it take a [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) reviewer to review a specific change request?

**Context Tags:** Contribution, Lifecycle

**Keywords:** Change Request Review, Change Request, Code Review, Time, Pull Request

## Description
The Change Request Review Duration metric measures the time from when a submitter has submitted a change within a [review cycle](https://chaoss.community/metric-review-cycle-duration-within-a-change-request/) until it is reviewed. This metric measures one review, however, there may be multiple reviews within a [Review Cycle Duration within a Change Request](https://chaoss.community/metric-review-cycle-duration-within-a-change-request/) and this measures time of each review. The time waiting for a review is zero if the change request is merged without any requested revisions or clarification.
## Objectives
Long waiting periods for a [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) review may indicate potential lack of experience by a maintainer, lack of time, hesitation on the part of the maintainer, or any other blocker. Delayed reviews in a community may cause a decline of interest by potential contributors or cause original changes to be out-of-sync with the rest of the code base. The Change Request Review Duration metric helps identify: 

Maintainer workload adequacy and potential for burnout
Whether delays are the responsibility of a reviewer
Discrepancies in review times for different contributors to indicate whether the review process is inclusive.

## Implementation
*The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other law. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md) for additional guidance.*
### Filters
- Change Request Review Duration can be filtered by:
- Reviewer (e.g., name or id)
- Reviewer role (e.g., maintainer, reviewer, and member)
- Bot reviews 
- Date and time the [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) was submitted or modified
- Date and time of the response
- [change request](https://github.com/chaoss/wg-evolution/blob/main/focus-areas/code-development-process-quality/change-requests.md) type and size may affect the response time.

### Visualization

![Augur Image](https://github.com/chaoss/wg-common/blob/main/focus-areas/time/images/change-request-review-duration_img1.png)

Figure - Source: [Augur Image API](http://augur.chaoss.io/api/unstable/pull_request_reports/mean_response_times_for_PR?repo_id=25440) & [Documentation]( https://oss-augur.readthedocs.io/en/main/rest-api/api.html#operation/Mean%20Response%20Times%20for%20Closed%20Pull%20Requests)

### Tools Providing the Metric
- Augur 
- GrimoireLab

## References
- [Code Review Decision Fatigue](https://tylercipriani.com/blog/2022/03/12/code-review-procrastination-and-clarity/)


## Contributors 
* Vinod Ahuja
* Dawn Foster
* Elizabeth Barron
* Kevin Lumbard
* Matt Germonprez
* Sean Goggins
