# Organizational Diversity

Question: What is the organizational diversity of contributions?

Context Tags: 

Keyword Tags:

## Description

Organizational diversity expresses how many different organizations are involved in a project and how involved different organizations are compared to one another.

##  Objectives

Contributors are employed by a variety of organizations, which can influence the direction of the project. Organizational diversity looks at the organizations contributing to a project, including the percentage of contributions from each organization within a defined period of time to see the change of composition of organizations within a defined period of time. As part of organizational diversity, it is also useful to look at the people that are associated with each organization.

Organizational diversity may impact the inclusivity of a project either positively or negatively. If an organization is employing people to work on open source, those people might come from more diverse backgrounds than projects that rely on people to have free time as volunteer contributors. If a single company dominates the project, others might not feel included or welcome. 

## Implementation
*The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other law. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md) for additional guidance.* 

* Collect data from data sources where contributions occur.
* Identify contributor affiliations to get a good estimate of which organizations they belong to.
* Correlate information about contributions, assigning each to appropriate organization.
* Depending on the needs of the project, you may want to consider such issues as how to handle multiple email addresses, affiliation changes over time, or contractor vs. employee.

### Visualizations

![Organizational Diversity Pie Chart](https://github.com/chaoss/wg-common/blob/main/focus-areas/people/images/organizational-diversity_piechart.png)

### Tools Providing the Metric

[GrimoireLab](https://chaoss.github.io/grimoirelab) supports organizational diversity metrics out of the box. The [GrimoireLab SortingHat](https://github.com/chaoss/grimoirelab-sortinghat) manages identities. The [GrimoireLab Hatstall](https://github.com/chaoss/grimoirelab-hatstall) user interface allows correcting organizational affiliation of people and even recording affiliation changes.
  * View an example visualization on the [CHAOSS instance of Bitergia Analytics](https://chaoss.biterg.io/app/kibana#/dashboard/Community-Structure-by-Organization).
  * Download and import a ready-to-go dashboard containing examples for this metric visualization from the [GrimoireLab Sigils panel collection](https://chaoss.github.io/grimoirelab-sigils/panels/community-structure-by-organization/).

* [LF Analytics](https://lfanalytics.io) provides organization diversity metrics in the primary view for commits, issues filed, and communication channels (current support for Slack and groups.io)

![Organizational Diversity View](https://github.com/chaoss/wg-common/blob/main/focus-areas/people/images/organizational-diversity_lfanalytics-orgdiversity.png) 

### Data Collection Strategies

**Qualitative**

* Footprint of an organization in a project or ecosystem
* Influence of an organization in a project or ecosystem
* Affiliation diversity in governance structures.

**Quantitative**

* % of commits by each organization
* % of merges/reviews from each organization
* % of any kind of contributors from each organization
* % of lines of code contributed by each organization
* % issues filed by each organization
* New Contributor Organizations - New organizations contributing to the project over time.
* Number of Contributing Organizations - Number of organizations participating in the project over time.
* [Elephant Factor](https://chaoss.community/metric-elephant-factor/) - If 50% of community members are employed by the same company, it is the elephant in the room. Formally: The minimum number of companies whose employees perform 50% of the commits
* Affiliation Diversity - Ratio of contributors from a single company over all contributors. Also described as: Maintainers from different companies. Diversity of contributor affiliation.
* In projects with the concept of code ownership, % of code owners affiliated with each organization weighed by the importance/size/LoC of the code they own and the number of co-owners.

## References

**Potential implementations and references:**
* [https://bitergia.gitlab.io/panel-collections/open_source_program_office/organizational-diversity.html](https://bitergia.gitlab.io/panel-collections/open_source_program_office/organizational-diversity.html)
* [Kata Containers dashboard entry page](https://katacontainers.biterg.io) (bottom of this)
* [Augur](https://github.com/chaoss/augur)
* [Drupal](​​https://dri.es/who-sponsors-drupal-development-2020)

## Known Contributors
Dawn Foster
Kevin Lumbard
Vinod Ahuja
Elizabeth Barron
Sean Goggins
Matt Germonprez
Georg Link

***This metric was last reviewed on September 1 as part of our recurring review process***

