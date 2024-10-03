# **Contributors**

**Question:** Who are the contributors to a project?

## **Overview**
A contributor is defined as anyone who contributes to the project in any way. This metric ensures that all types of contributions are fully recognized within the project. Identifying contributors helps the community recognize and celebrate various contributions, from code development to event planning and marketing efforts.

Recognizing the contributors is vital to understanding who is driving different activities and informs project health by showing diversity and breadth in project involvement.

## **Want to Know More?**

<span markdown="1"><details>
<summary>Click to read more about this metric.</summary>

### **Data Collection Strategies**

- **Surveys and Interviews**:
Some contributor information is available via software such as GrimoireLab and Augur. However, some contributor insights are less easily obtained via trace data. In these cases, surveys with community members or event registrations can provide the desired information. Sample questions include:
   - *Which contributors do not typically appear in lists of contributors?*
   - *Which contributors are often overlooked because their contributions are more “behind the scenes”?*
   - *Who are the community members you work with regularly?*

Surveys with Likert scale or matrix formats can also provide insights into contributor activity levels. Sample questions for community members:
- Likert scale [1-x]: I am contributing to the project.
- Matrix survey item: How often do you engage in the following activities in the project?
   - Columns: Never, Rarely (less than once a month), Sometimes (more than once a month), Often (once a week or more)
   - Rows: a) Contributing/reviewing code, b) Creating or maintaining documentation, c) Translating documentation, d) Participating in decision-making, e) Serving as a community organizer, f) Mentoring, g) Attending events, h) Participating through school or university computing programs, i) Participating through a program like Outreachy, Google Summer of Code, etc., j) Helping with the ASF operations (e.g., board meetings or fundraising)
- **Aggregators:** Collect contributor names from collaboration tools, such as source code repositories, issue trackers, event registrations, mailing lists or any other tools a project uses.
   - *Count:* Total number of contributors during a given time period.
- **Parameters:**
   - *Period of time:* Start and end dates for the period in which contributions are counted (default: forever).
- **Data Sources:** Contributor data can be collected from collaboration platforms like GitHub, GitLab, IRC, blogs, and forums, or from tools like GrimoireLab and Augur.

### **Filters**
Contribution data can be filtered in several ways, such as:
- By the location of engagement:
   - Commit authors
   - Issue authors
   - Review participants (e.g., pull requests)
   - Mailing list authors
   - Event participants
   - IRC or forum authors
- By project characteristics:
   - By release cycle
   - Programming languages of the project
   - Role or function in the project (e.g., coding, organizing, mentoring)
   - Timeframe of activity (e.g., identifying new contributors)

### **Visualizations**
1. List of contributor names (often with information about their level of engagement)

![Contributor names and info](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/people/images/contributors_top-contributor-info.png)
 
  *Figure 1: List of contributors and engagement ()*

2. Summary number of contributors

![Summary number of contributors](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/people/images/contributors_summary-contributor-number.png)

   *Figure 2: Summary number of contributors ()*

3. Change in the number of active contributors over time

![Contributor growth](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/people/images/contributors_growth.png)

*Figure 3: Change in number of active contributors over time ()*

4. New contributors (sort list of contributors by date of first contribution)

![New contributors](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/people/images/contributors_first-commit-date.png)

*Figure 4: Contributor growth over time ()*

</details></span>

## **References**
None specified.

## **Contributors**
- Kevin Lumbard
- Vinod Ahuja
- Elizabeth Barron
- Dawn Foster
- Sean Goggins
- Matt Germonprez
- Yigakpoa L. Samuel (Ikpae)

## **Additional Information**
- To edit this metric please submit a Change Request here: https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/people/contributors.md
- To reference this metric in software or publications please use this stable URL: https://chaoss.community/?p=3467


<!-- # For groupings in the knowledge base
Context tags: Author, Contributor Recognition, Project Health, Community Engagement, Project Involvement Metrics, Contributor Roles
Keyword tags: Committer, Participant, Contributors, Contribution Tracking, Project Contributors, Contributor Growth, New Contributors
-->
