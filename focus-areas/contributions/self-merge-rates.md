# Technical Fork
Question: How many of the contributions in the project repository are being merged by the original contributor?

## Description
This metric measures the number of [change requests](https://chaoss.community/?p=3610) merged by the author and merged without going through a [change request review](https://chaoss.community/?p=4712) process. 

## Objectives
Healthy and collaborative projects will have a culture of doing reviews of all contributions regardless of who – from first-time contributors to project creators–made the contribution in the repository. Including reviews in any changes to the code reinforces the merge process for newcomers and ensures that another person has seen and agreed with the change to be made. Ideally, you should not see any self merges or merges without review in a repository unless there is a valid reason that is agreed to in the community (e.g., a simple typo fix). 

* Community managers would be interested in seeing if a community is making progress in their review health. (e.g., did the self merge rate go down this year vs. last year?)
* Community managers would be interested in seeing if the number of community members involved in change requests/reviews is changing over time. 
* OPSO managers want to understand what open source projects to incorporate into their solutions by evaluating project’s review health.  
* Anyone (e.g., potential users or community members) interested in evaluating the health of the community would want to see the self merge and merge without review rate trends over time and see if there's a healthy review of contributions in the repository. 

## Implementation

### Filters 
* Merge without review
* Lines of code changed
* File type changed (e.g., code vs. documentation)
* Volume/size of reviews
* Time
  
### Visualizations

### Tools Providing the Metric  
* GitHub interface  
* GitLab interface  

### Data Collection Strategies 

* Existence of automated reviews (e.g., non-bot and non-rule based reviews): there should be reviews with text-based comments, emoji’s, or assigned reviewer approval.  

## References


## Known Contributors
* Ray Paik
* Matt Germonprez 
* Kevin Lumbard
* Elizabeth Barron
* Dawn Foster
