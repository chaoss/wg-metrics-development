# Technical Fork
Question: What are a number of technical forks of an open source project on code development platforms?

## Description
A technical fork is a distributed version control copy of a project. The number of technical forks indicates the number of copies of a project on the same code development platform.

**Note:**  Many times technical fork and [clones](https://chaoss.community/metric-clones/) are used interchangeably, but there is a difference between the two. A technical fork is a copy of a repository on the same platform, whereas a [clone](https://chaoss.community/metric-clones/) is a copy on a local machine.

![Technical Fork & Clones](https://raw.githubusercontent.com/chaoss/wg-common/main/focus-areas/contributions/images/technical-fork-clones_fork-clones.png)

[Image is sourced from Stakeoverflow](https://stackoverflow.com/questions/9257533/what-is-the-difference-between-origin-and-upstream-on-github/9257901#9257901)

## Objectives
The objective of the Technical Fork metric is to ascertain how many copies of a project exist on a code development platform. Analysis of technical forks may provide insight into forking intentions (different types of forks such as contributing, and non-contributing forks).

## Implementation
*The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other law. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md) for additional guidance.*

### Filters
* Time Period (e.g., Weekly, Monthly, Annually)  
* Ratio of contributing fork to total forks (A contributing fork is a fork that has opened a change request against the original repository.)  
* Ratio of non-contributing fork to total forks (A non-contributing fork is a fork that has never opened a change request against the original repository.)  

### Visualizations
**Augur Implementation**

![Augur Implementation](https://raw.githubusercontent.com/chaoss/wg-common/main/focus-areas/contributions/images/technical-fork_augur-fork.png)

**GrimoireLab Implementation**

![GrimoireLab Implementation](https://raw.githubusercontent.com/chaoss/wg-common/main/focus-areas/contributions/images/technical-fork_grimoirelab-fork.png)

### Tools Providing the Metric  
* Augur  
* GrimoireLab  

## References
* [Fork a repo](https://help.github.com/en/enterprise/2.13/user/articles/fork-a-repo)
* [What's the difference between a fork and clone?](https://opensource.com/article/17/12/fork-clone-difference)
* [Github API](https://developer.github.com/v3/repos/forks/#list-forks)
* [GitLab API](https://docs.gitlab.com/ee/api/projects.html#fork-project)
* [Bitbucket API](https://developer.atlassian.com/cloud/bitbucket/rest/api-group-repositories/#api-repositories-workspace-repo-slug-forks-get)

## Contributors
* Vinod Ahuja
* Sean Goggins 
* Matt Germonprez
* Kevin Lumbard
* Dawn Foster 
* Elizabeth Barron


**This metric was last reviewed on September 1, 2022 as part of recurring review process.**

