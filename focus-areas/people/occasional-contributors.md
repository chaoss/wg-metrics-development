# Occasional Contributors

### This metric is a release candidate. To comment on this metric please see Issue [#[160]](https://github.com/chaoss/wg-common/issues/160). Following a comment period, this metric will be included in the next regular release.

Question: How do we understand the number of occasional contributors and the contributions that they make?

Synonyms: drive-through contributors; fly-by contributors, episodic contributors

## Description
Occasional contributors are those who make contributions to a project on an irregular basis. Occasional contributors are important to recognize in a community as their contributions can serve to advance the project in meaningful ways. One precise definition of an occasional contributor is “someone who hasn’t submitted a pull request in at least 3 months and hasn’t had more than 12 pull requests overall in the project” [1]. 

Motivations for being an occasional contributor:
- Self-service: A person has a bug they need fixed, so they submit an issue or a fix. 
- Work-related: A person works for a company and the company requires a fix or feature. 
- Special project or use case: A person needs to get their project to run on Commodore 64 or Atari 800XL.
- Documentation addition/fix: A person is fixing a typo.
- Hackathon, workshop, or other event: A person is participating in a time-boxed event for a specific purpose or goal.
- Suboptimal Onboarding: A person may have intended to stick around, but decided that the community or project was not a good fit for them.
- Life Event: A person may have intended to stick around, but may have experienced a life event that limited their participation in open source.

## Objectives
Monitoring occasional contributors can help you understand if:
- More people are looking at the project 
- More people are using the project 
- The contribution process is working well
- More people are able to contribute to the project 
- More contributors exist to convert to dependable community members 

All of which can help you improve your understanding of the health of your project.

## Implementation

The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other law. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see CHAOSS Data Ethics document for additional guidance

### Filters
- Minimum number of contributions before someone is no longer an occasional contributor. 
- Maximum length of time between contributions before someone is no longer considered an occasional contributor 
- Percentage of overall contributors who are classified as occasional contributors
- Repeat occasional contributors 

### Visualizations

![Occasional Contributors Augur](https://github.com/chaoss/wg-common/blob/main/focus-areas/people/images/occasional-augur.png)

From Augur, Endpoint https://tinyurl.com/augur-flyby 
Augur API Documentation: https://tinyurl.com/augur-flyby-docs 

![Occasional Contributors Cauldron](https://github.com/chaoss/wg-common/blob/main/focus-areas/people/images/occasional-caudron.png)

From: https://cauldron.io/

### Tools Providing the Metric
- [Cauldron.io](https://cauldron.io/)
- [Devstats](https://devstats.cncf.io/)
- [Augur](https://github.com/chaoss/augur)

## References
[1] https://k8s.devstats.cncf.io/d/18/new-and-episodic-pr-contributors?orgId=1 
Have It Your Way: Maximizing Drive-Thru Contributions by VM Brasseur 

## Contributors
- Matt Germonprez
- Regina Nkemchor Adejo
- Dawn Foster
- Kevin Lumbard
- Vinod Ahuja

***This metric was last reviewed on March 1, 2022 as part of the 202204 release***
