# Clones

Question: How many copies of an open source project repository have been saved on a local machine?

## Description
A clone is a copy of a repository saved to a local machine.

**Note:**  Many times clone and [technical fork](https://github.com/chaoss/wg-common/blob/master/focus-areas/what/technical-fork.md) are used interchangeably, but there is a difference between the two. A [technical fork](https://github.com/chaoss/wg-common/blob/master/focus-areas/what/technical-fork.md) is a copy of a repository on the same platform, whereas a clone is a copy on a local machine.

![Technical Fork & Clones](images/technical-fork-clones_fork-clones.png)

[Image is sourced from Stakeoverflow](https://stackoverflow.com/questions/9257533/what-is-the-difference-between-origin-and-upstream-on-github/9257901#9257901)

## Objectives
The objective of the Clones metric is to ascertain how many copies of a project are downloaded. Analysis of clones may provide insight into the [project's popularity](https://github.com/chaoss/wg-value/blob/master/focus-areas/communal-value/project-popularity.md) and usage. 

## Implementation

### Filters 
* Time Period (e.g., clones by week, month, year)
* Partial clones (offered by gitlab https://docs.gitlab.com/ee/topics/git/partial_clone.html#partial-clone)

### Visualizations 
 
![GitHub Clones](images/clones_github_clones.png)

[Image is source from Github Blog](https://github.blog/2014-08-12-clone-graphs/)


## References
* [What is the difference between forking and cloning a repository?](https://github.community/t/the-difference-between-forking-and-cloning-a-repository/10189)
* [What's the difference between a fork and clone?](https://opensource.com/article/17/12/fork-clone-difference) 
* [Github API]**(**[https://docs.github.com/en/rest/reference/repos#get-repository-clones](https://docs.github.com/en/rest/reference/repos#get-repository-clones)**)**

## Contributors
* Vinod Ahuja
* Sean Goggins 
* Matt Germonprez
* Kevin Lumbard
* Dawn Foster 
* Elizabeth Barron
