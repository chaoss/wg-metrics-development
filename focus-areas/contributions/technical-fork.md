# Technical Fork

**Question:** What are a number of technical forks of an open source project on code development platforms?

## Overview

Technical Fork metric measures the number of independent copies of a project repository within the same code development platform. Data points consist of the count of distinct technical forks created from the original repository.
A technical fork is a distributed version control copy of a project. Unlike [clones](https://chaoss.community/metric-clones/), which is a copy on a local machine, a technical fork resides on the same platform as the original repository. Analysis of technical forks may provide insight into forking intentions (e.g., contributing vs. non-contributing forks). A high number of technical forks may indicate a strong interest in the project, a vibrant community, and opportunities for collaboration and innovation.

## Want to Know More?

<span markdown="1"><details>

<summary>Click to read more about this metric.</summary>

### Filters

*   Time Period (e.g., Weekly, Monthly, Annually)
*   Ratio of contributing fork to total forks (A contributing fork is a fork that has opened a change request against the original repository.)
*   Ratio of non-contributing fork to total forks (A non-contributing fork is a fork that has never opened a change request against the original repository.)

### Visualizations

[Technical Fork & Clones](https://stackoverflow.com/questions/9257533/what-is-the-difference-between-origin-and-upstream-on-github/9257901#9257901)

![Image is sourced from Stakeoverflow](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/contributions/images/technical-fork-clones_fork-clones.png)

**Augur Implementation**

![Augur Implementation](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/contributions/images/technical-fork_augur-fork.png)

**GrimoireLab Implementation**

![GrimoireLab Implementation](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/contributions/images/technical-fork_grimoirelab-fork.png)

</details></span><br>

## References

*   [Fork a repo](https://help.github.com/en/enterprise/2.13/user/articles/fork-a-repo)
*   [What's the difference between a fork and clone?](https://opensource.com/article/17/12/fork-clone-difference)
*   [Github API](https://developer.github.com/v3/repos/forks/#list-forks)
*   [GitLab API](https://docs.gitlab.com/ee/api/projects.html#fork-project)
*   [Bitbucket API](https://developer.atlassian.com/cloud/bitbucket/rest/api-group-repositories/#api-repositories-workspace-repo-slug-forks-get)

## Contributors

*   Vinod Ahuja
*   Sean Goggins
*   Matt Germonprez
*   Kevin Lumbard
*   Dawn Foster
*   Elizabeth Barron
*   Peculiar C. Umeh

## Additional Information

To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/contributions/technical-fork.md)

To reference this metric in software or publications please use this stable URL: <https://chaoss.community/?p=3431>

<!-- # For groupings in the knowledge base
Context tags: Platform, Software
Keyword tags: Fork, Clone, Copy, Download
-->
