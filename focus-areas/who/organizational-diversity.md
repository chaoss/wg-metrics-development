# Organizational Diversity

Question: What is the organizational diversity of contributions?

## Description

Organizational diversity expresses how many different organizations are involved in a project and how involved different organizations are compared to one another.

##  Objectives

* Get a list of organizations contributing to a project.
* See the percentage of contributions from each organization within a defined period of time.
* See the change of composition of organizations within a defined period of time.
* Get a list of people that are associated with each organization.

## Implementation

* Collect data from data sources where contributions occur.
* Identify contributor affiliations to get a good estimate of which organizations they belong to.
* Correlate information about contributions, assigning each to appropriate organization.
* Depending on the needs of the project, you may want to consider such issues as how to handle multiple email addresses, affiliation changes over time, or contractor vs. employee.

### Tools Providing the Metric

* [GrimoireLab](https://chaoss.github.io/grimoirelab) supports organizational diversity metrics out of the box. The [GrimoireLab SortingHat](https://github.com/chaoss/grimoirelab-sortinghat) manages identities. The [GrimoireLab Hatstall](https://github.com/chaoss/grimoirelab-hatstall) user interface allows correcting organizational affiliation of people and even recording affiliation changes.
  * View an example visualization on the [CHAOSS instance of Bitergia Analytics](https://chaoss.biterg.io/app/kibana#/dashboard/Community-Structure-by-Organization).
  * Download and import a ready-to-go dashboard containing examples for this metric visualization from the [GrimoireLab Sigils panel collection](https://chaoss.github.io/grimoirelab-sigils/panels/community-structure-by-organization/).
  * Add a sample visualization to any GrimoreLab Kibiter dashboard following these instructions:
    * Create a new Pie chart
      * Select the `all_onion` index
      * Metrics Slice Size: `Sum` Aggregation, `contributions` Field, `Contributions` Custom Label
      * Buckets Split Slices: `Terms` Aggregation, `author_or_name` Field, `metric: Contributions` Order By, `Descending` Order, `500` Size, `Organization` Custom Label
    * Example Screenshot

    ![Organizational Diversity Pie Chart](images/organizational-diversity_piechart.png)

* [LF Analytics](https://lfanalytics.io) provides organization diversity metrics in the primary view for commits, issues filed, and communication channels (current support for Slack and groups.io)

![Organizational Diversity View](images/organizational-diversity_lfanalytics-orgdiversity.png)



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
* [Contributing Organizations](https://github.com/chaoss/metrics/blob/master/activity-metrics/contributing-organizations.md) - What is the number of contributing organizations?
* [New Contributing Organizations](https://github.com/chaoss/metrics/blob/master/activity-metrics/new-contributing-organizations.md) - What is the number of new contributing organizations?
* New Contributor Organizations - New organizations contributing to the project over time.
* Number of Contributing Organizations - Number of organizations participating in the project over time.
* Elephant Factor - If 50% of community members are employed by the same company, it is the elephant in the room. Formally: The minimum number of companies whose employees perform 50% of the commits
* [Affiliation Diversity](https://github.com/chaoss/metrics/blob/master/activity-metrics/contributor-diversity.md) - Ratio of contributors from a single company over all contributors. Also described as: Maintainers from different companies. Diversity of contributor affiliation.
* In projects with the concept of code ownership, % of code owners affiliated with each organization weighed by the importance/size/LoC of the code they own and the number of co-owners.

## References
* Potential implementations and references:
  * [https://bitergia.gitlab.io/panel-collections/open_source_program_office/organizational-diversity.html](https://bitergia.gitlab.io/panel-collections/open_source_program_office/organizational-diversity.html)
  * [Kata Containers dashboard entry page](https://katacontainers.biterg.io) (bottom of this)
  * [Augur](https://github.com/chaoss/augur)
