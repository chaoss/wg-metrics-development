# Release Frequency

**Question:** How often does a project publish a release of their software / artifact?

## Overview

Release Frequency measures the frequency of project software / artifact releases over time. This includes the major releases and smaller point releases that might contain bug fixes and security updates. Each releases is expected to contain new features, bug fixes, and security updates. Releasing updates that contain accessibility features or bug fixes that impact accessibility could have a positive impact on Diversity Equity and Inclusion (DEI) when they are released quickly or a negative impact when accessibility updates are delayed. Delays in incorporating changes into a release, especially when the changes contain security updates, can mean that users don’t have an easy way to upgrade from an insecure version and are open to malicious attacks or other vulnerabilities.
A higher frequency of releases indicates that software artifacts are iterating rapidly to respond to user needs. Release frequency is highly variable because software projects belong to different industries and fields, and no two projects have the same needs. A consistent release frequency may indicate a more stable or mature project.

## Want to Know More?

<span markdown="1"><details>

<summary>Click to read more about this metric.</summary>

### Data Collection Strategies

In many cases, this data can be collected from the same platform as the source code (e.g., GitHub, GitLab, Gitee); however, some projects may also release code via package managers, web pages, or other locations. The data collection should align with where the project publishes their releases and makes them available to their customers.

### Filters

*   Type of release. E.g., major, minor, bug fix, pre-release, alpha, or based on semantic versioning.
*   Tag name.
*   Count. Total number of releases during the period.
*   Dates. Creation, publication.
*   Period of time. Start and finish date of the period.
*   Size. Bytes or lines of code.

### Visualizations

*   Count per time period (i.e., weeks, months, years) over time
    These could be grouped by applying the filters defined above. These could be represented as bar charts or as individual points with time running in the X axis.

[OSS-Compass](https://oss-compass.org/):
![OSS Compass Recent Releases Count visualization](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/images/release-frequency-oss-compass.png)

Augur data using Python:
![Releases visualized across time using data from Augur graphed using Python scripts](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/images/release-frequency-python-augur.png)

</details></span><br>

## References

*   [Semver](https://semver.org/)
*   [OSS-Compass](https://oss-compass.org/)
*   [CHAOSScon NA 2021 Lightning Talk](https://www.youtube.com/watch?v=DynqP2_W1ts)

## Known Contributors

*   Dawn Foster
*   Yehui Wang
*   Sean Goggins
*   Elizabeth Barron
*   Matt Germonprez
*   Vinod Ahuja
*   Kevin Lumbard
*   Peculiar C Umeh

## Additional Information

To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/time/release-frequency.md)

To reference this metric in software or publications please use this stable URL: <https://chaoss.community/?p=4765>

<!-- # For groupings in the knowledge base
Context tags: Lifecycle, Software
Keyword tags:release, bug fixes, security, version, release cycle, cadence
-->
