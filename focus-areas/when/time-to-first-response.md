# Time to First Response 

Question: How much time passes between when an activity requiring attention is created and the first response? 


## Description

The first response to an activity can sometimes be the most important response. The first response shows that a community is active and engages in conversations. A long time to respond to an activity can be a sign that a community is not responsive. A short time to respond to an activity can help to engage more members into further discussions and within the community.


## Objectives

Identify cadence of first response across a variety of activities, including PRs, Issues, emails, IRC posts, etc.  Time to first response is an important consideration for new and long-time contributors to a project along with overall project health. 


## Implementation

Time to first response of an activity = time first response was posted to the activity - time the activity was created. 


### Filters

* Role of responder, e.g., only count maintainer responses
* Automated responses, e.g., only count replies from real people by filtering bots and other automated replies
* Type of Activity, e.g., issues (see metric [Issue Response Time](https://github.com/chaoss/wg-evolution/blob/master/metrics/Issue_Response_Time.md)), emails, chat, change requests


### Visualizations
![GrimoireLab Panel: Efficiency Timing Overview](images/time-to-first-response_efficiency-timing-overview.png)
---------
![Augur Visualization: Time to First Response Heat Map ](images/time-to-first-response_augur-ttc-1.png)
---------
![Augur Visualization: Mean Response Times](images/time-to-first-response_augur-ttc-2.png)

### Tools Providing the Metric

* GrimoireLab Panel: [Efficiency Timing Overview](https://chaoss.github.io/grimoirelab-sigils/panels/efficiency-timing-overview/)
* [Kata Containers dashboard efficiency panel](https://katacontainers.biterg.io/app/kibana#/dashboard/cbbdd920-288c-11e9-b662-975152e57997)

## References


