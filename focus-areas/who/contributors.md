# Contributors

Question: Who are the contributors to a project?

## Description

A contributor is defined as anyone who contributes to the project in any way. This metric ensures that all types of contributions are fully recognized in the project.

## Objectives

Open source projects are comprised of a number of different contributors. Recognizing all contributors to a project is important in knowing who is helping with such activities as code development, event planning, and marketing efforts.  

## Implementation

Collect author names from collaboration tools a project uses.

**Aggregators:**
* Count. Total number of contributors during a given time period.

**Parameters:**
* Period of time. Start and finish date of the period. Default: forever.
 Period during which contributions are counted.

### Filters

By location of engagement. For example:
* Commit authors
* Issue authors
* Review participants, e.g., in pull requests
* Mailing list authors
* Event participants
* IRC authors
* Blog authors
* By release cycle
* Timeframe of activity in the project, e.g, find new contributors
* Programming languages of the project 
* Role or function in project

### Visualizations

1. List of contributor names (often with information about their level of engagement)<br />
![Contributor names and info](images/contributors_top-contributor-info.png)

2. Summary number of contributors<br />
![Summary number of contributors](images/contributors_summary-contributor-number.png)

3. Change in the number of active contributors over time<br />
![Contributor growth](images/contributors_growth.png)

4. New contributors (sort list of contributors by date of first contribution)<br />
![New contributors](images/contributors_first-commit-date.png)

### Tools Providing the Metric

* [GrimoireLab](https://chaoss.github.io/grimoirelab/)
* [Augur](http://augur.osshealth.io/api_docs/#api-Evolution-Contributors_Repo_)

### Data Collection Strategies

As indicated above, some contributor information is available via software such as GrimoireLab and Augur. However, some contributor insights are less easily obtained via trace data. In these cases, surveys with community members or event registrations can provide the desired information. Sample questions include:

* Interview question: Which contributors do not typically appear in lists of contributors? 
* Interview question: Which contributors are often overlooked as important contributors because their contributions are more “behind the scenes”?
* Interview question: What other community members do you regularly work with?

Additionally, surveys with community members can provide insight to learn more about contributions to the project. Sample questions include:

* Likert scale [1-x] item: I am contributing to the project
* Matrix survey item: How often do you engage in the following activities in the project? 
  * Column headings: Never, Rarely(less than once a month), Sometimes (more than once a month), Often(once a week or more)
  * Rows include: a) Contributing/reviewing code, b) Creating or maintaining documentation, c) Translating documentation, d) Participating in decision making about the project’s development, e) Serving as a community organizer, f) Mentoring other contributors, g) Attending events in person, h) Participating through school or university computing programs, i) Participating through a program like Outreachy, Google Summer of Code, etc., j) Helping with the ASF operations (e.g., board meetings or fundraising) 

## References
