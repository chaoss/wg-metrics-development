# Technical Fork
Question: What are a number of technical forks of an open source project on code development platforms?

## Description
A technical fork is a distributed version control copy of a project. The number of technical forks indicates the number of copies of a project on the same code development platform.

**Note:**  Many times technical fork and [clones](https://github.com/chaoss/wg-common/blob/master/focus-areas/contributions/clones.md) are used interchangeably, but there is a difference between the two. A technical fork is a copy of a repository on the same platform, whereas a [clone](https://github.com/chaoss/wg-common/blob/master/focus-areas/contributions/clones.md) is a copy on a local machine.

![Technical Fork & Clones](images/technical-fork-clones_fork-clones.png)

[Image is sourced from Stakeoverflow](https://stackoverflow.com/questions/9257533/what-is-the-difference-between-origin-and-upstream-on-github/9257901#9257901)

## Objectives
The objective of the Technical Fork metric is to ascertain how many copies of a project exist on a code development platform. Analysis of technical forks may provide insight into forking intentions (different types of forks such as contributing, and non-contributing forks).

## Implementation

### Filters
* Time Period (e.g., Weekly, Monthly, Annually)  
* Ratio of contributing fork to total forks (A contributing fork is a fork that has opened a change request against the original repository.)  
* Ratio of non-contributing fork to total forks (A non-contributing fork is a fork that has never opened a change request against the original repository.)  

### Visualizations
**Augur Implementation**

![Augur Implementation](images/technical-fork_augur-fork.png)

**GrimoireLab Implementation**

![GrimoireLab Implementation](images/technical-fork_grimoirelab-fork.png)

### Tools Providing the Metric  
* Augur  
* GrimoireLab  

## References
* https://help.github.com/en/enterprise/2.13/user/articles/fork-a-repo
* https://opensource.com/article/17/12/fork-clone-difference
* Github API (**https://developer.github.com/v3/repos/forks/#list-forks**)
* GitLab API (**https://docs.gitlab.com/ee/api/projects.html#list-forks-of-a-project**)
* Bitbucket API (**https://developer.atlassian.com/bitbucket/api/2/reference/resource/repositories/%7Bworkspace%7D/%7Brepo_slug%7D/forks**)

## Contributors
* Vinod Ahuja
* Sean Goggins 
* Matt Germonprez
* Kevin Lumbard
* Dawn Foster 
* Elizabeth Barron
