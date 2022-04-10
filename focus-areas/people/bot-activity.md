# Bot Activity 

Question: What is the volume of automated bot activity?

## Description
A bot is a piece of software that supports project activities. Bots provide an increasingly important role in open source projects, helping coordinate open source project work. Bots support various workflows including issue and merge request management and contributor agreements. Bots give open source software projects numerous options in deciding how to effectively manage project work. 

## Objectives
The Bot Activity metric helps differentiate project activity between people and automated applications (e.g., bots). In doing so, community managers can better seperate such things as increases in new contributors, CLA bot activity, and bot-related access control. This metric may provide additional context for:
* [Time to first response](https://chaoss.community/metric-time-to-first-response/)
* Build process timing 
* Social considerations -- it’s not just all robots 
* An indication of maturity
* Indication of community size 
* Indication of project transparency

## Implementation
*The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other law. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md) for additional guidance.*

* Ratio of bot to human activity over time
* Average number of bots over time 

### Filters 
* Bots that have user profiles
* Bots that require human interaction 
* Bots that function by themselves (automated) 
* Bots that assist with software development 
* Bots that assist with communication
* Bots that assist with access control
* Bots that assist with inclusivity 
* Platform where the bot is used (e.g., GitHub, Slack)

### Visualizations 

![k8s.devstats.cncf.io](https://user-images.githubusercontent.com/656208/130105428-f9a0cc9e-dc7a-43e3-a654-25261cb4cae8.png)  

From: https://k8s.devstats.cncf.io/d/5/bot-commands-repository-groups?orgId=1&var-period=w&var-repogroup_name=Kubernetes&var-repo_name=kubernetes%2Fkubernetes&var-commands=All


## References
- [6- Bots to Better Your Open Source Project](https://www.twilio.com/blog/6-bots-better-open-source-project)
- [GiHub’s Hubot](https://hubot.github.com/)

## Contributors
- Sean Goggins
- Matt Germonprez
- Kevin Lumbard
- Dawn Foster
- Elizabeth Barron
- Vinod Ahuja
- Matt Cantu
