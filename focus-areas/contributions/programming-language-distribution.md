# Programming Language Distribution

Question: What are the different programming languages present in an open source project(s), and what is the percentage of each language?

## Description

The number of programming languages and the percentage of each language in a project provides some understanding of the skills required from code contributors, as well as the nature of the project itself.

## Objectives

This metric will aid newcomers to a  particular open source project, as well as provide open source program managers with a perspective on the project’s profile, in the context of their own experience and organization.
- This metric may be used by developers for identifying projects that rely heavily on languages they use, as part of a job search.
- This metric can be useful for identifying changes in the number of files, or lines of code in each language over time. For example, a project may be X% Python, and Y% Javascript at a point in time. Perhaps a year later, the amount of Javascript measured by files, or lines of code, may be greater as a result of a project’s shift in focus toward user experience.
- This metric can be combined with dependency metrics to determine if there is a prominent language used in a project, but for which a dependency scanner is not yet identified.
- When inclusive, diverse, and equitable communities are identified, they will have some degree of language distribution.
- As an individual looks for new projects to work on, knowing which projects rely on languages they already know, or want to learn, can be one of a number of “personal filters”.
- This metric is useful for OSPOs, and community managers aiming to understand which languages are most prominent, and perhaps which languages are little used, but critical.

## Implementation

Language distribution takes into account different properties of each file in a repository with an a priori identifiable computer programming language. As new languages emerge, there may be initial periods where counting tools do not recognize their extensions, in which case they may be counted as “other”. Such periods are typically brief.  

### Filters

 - Time
 - Number of Files - The number of files of each language.

	![Number of Files Table](https://github.com/chaoss/wg-common/blob/main/focus-areas/contributions/images/language-distribution_number-of-files-table.png)

 - Lines of Code - The percentage of lines of code for each language.

	![Number of Files Table](https://github.com/chaoss/wg-common/blob/main/focus-areas/contributions/images/language-distribution_lines-of-code-table.png)


Either lines of code, or files, could be presented as absolute numbers, or percentages, depending on the application of the metric. In many cases, a simple count of files is useful, while the absolute number of lines of code can be difficult to differentiate because the numbers are much larger.


### Tools Providing the Metric

The [Augur-Community-Reports](https://github.com/chaoss/augur-community-reports) repository provides this metric currently

[GrimoireLab](https://github.com/chaoss/grimoirelab) provides this information through the proxy of file extensions

[Augur](https://github.com/chaoss/augur) provides this information in its frontend, as well as through an API endpoint.

### Data Collection Strategies

The contents of a repository can be counted by iterating through each file, though several libraries exist, including the one used by Augur: https://github.com/boyter/scc

File extensions for some languages, like Jupyter Notebooks, might be excluded because they obscure the actual language used.

## References

 - https://github.com/boyter/scc  

## Contributors
 - Dawn Foster
 - Beth Hancock
 - Matt Germonprez
 - Elizabeth Barron
 - Daniel Izquierdo
 - Kevin Lumbard
 - Sean Goggins

*The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other law. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md) for additional guidance.*
