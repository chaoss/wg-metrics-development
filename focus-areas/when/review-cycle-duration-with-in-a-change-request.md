# Review Cycle Duration within a Change Request

Question: What is the duration of a review cycle within a single change request?

## Description

A change request is based on one or more review cycles. Within a review cycle, one or more reviewers can provide feedback on a proposed contribution. The duration of a review cycle, or the time between each new iteration of the contribution, is the basis of this metric.

## Objectives
This metric provides maintainers with insight on:
Code review process decay, as there are more iterations and review cycle durations increase.
Process bottlenecks resulting in long code review iterations.
Abandoned or semi-abandoned processes in the review cycles, where either the maintainer or the submitter is slow in responding.
Characteristics of reviews that have different cyclic pattern lengths.
## Implementation
Review Cycle Duration is measured as the time length of one review cycle within a single change request.
The duration can be calculated between:
The moment when each review cycle begins, defined as the point in time when a change request is submitted or updated.
The moment when each review cycle ends, either because the change request was updated and needs a new review or because it was accepted or rejected.
### Filter

Average or Median Duration, optionally filtered or grouped by:
Number of people involved in review
Number of comments in review
Edits made to a change request
Project or program
Organization making the change request
Time the change request was submitted
Developers who contributed to a change request
Change request
Number of review cycle on a change request (e.g., filter by first, second, …  round)
### Visualizations
### Tools Providing the Metric

## References

Example of data that could be used to develop the metric: https://gerrit.wikimedia.org/r/c/mediawiki/core/+/194071
