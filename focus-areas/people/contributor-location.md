# Contributor Location

**Question:** What is the location of contributors?

## Overview

Contributor Location  measures the geographic locations which contributors contribute, where they live, or where they work. Tracking contributor location provides insights into the project's global reach, work practices, and time zone considerations.  Also, to identify where contributions do not come from in an effort to improve engagement in these areas. A project with contributors from diverse geographic locations may indicate a more inclusive and equitable environment.

## Want to Know More?

<span markdown="1"><details>

<summary>Click to read more about this metric.</summary>

### Data Collection Strategies

Different approaches can be used to collect information about location:

*   Collect the location information from a contributor’s profile in the system of engagement.
*   Use IP address geolocation of the most frequent locations that contributions are made.
*   Infer geographical location from the timestamp in contributions.
*   Survey contributors.

The key challenge for collecting data is determining the location of the contributor. Best practice would be to leverage any profile information available from the system of engagement, and if that is not available then use IP geolocation to determine the most frequent location of contribution from that individual. Note that contributors may enter in their profile information false or nonsensical location information (e.g., “Earth” or “Internet”). Note that IP geolocation can provide large numbers of false positives due to use of VPNs or other IP masking tools.

An additional consideration would be the use of external data collection tools such as community surveys or event registration data that could cross reference systems of engagement profiles. Contributor location data could be collected inline with event [attendee demographics](https://chaoss.community/metric-attendee-demographics/) and [speaker demographics](https://chaoss.community/metric-speaker-demographics/).

### Filters

Filter contributions by:

*   **Location.** Attempt to group locations in regions to have multiple levels of reporting. Location is a purposely ambiguous term in this context, and could refer to region, country, state, locale, or time zone.
*   **Period of time.** Start and finish date of the period. Default: forever. Period during which contributions are counted.
*   **Type of contributor**, for example:
    *   Repository authors
    *   Issue authors
    *   Code review participants
    *   Mailing list authors
    *   Event participants
    *   IRC authors
    *   Blog authors
    *   By release cycle
    *   Programming languages of the project
    *   Role or function in project

### Visualizations

[Dot Density Map](https://chaoss.biterg.io/goto/a62f3584a41c1c4c1af5d04b9809a860)

![Contributor Location Dot Density Map](https://github.com/chaoss/wg-common/blob/main/focus-areas/people/images/contributor-location_dot-density-map.png)

[Visual heat map:](https://blog.bitergia.com/2018/11/20/ubers-community-software-development-analytics-for-open-source-offices)

![Contributor Location Heatmap](https://github.com/chaoss/wg-common/blob/main/focus-areas/people/images/contributor-location_heatmap.png)

</details></span><br>

## References

*   Gonzalez-Barahona, J. M., Robles, G., Andradas-Izquierdo, R., & Ghosh, R. A. (2008).
*   Geographic origin of libre software developers. *Information Economics and Policy*, *20*(4), 356-363.

## Contributors

*   Matt Germonprez
*   Kevin Lumbard
*   Peculiar C. Umeh

## Additional Information

To edit this metric please [submit a Change Request here](https://github.com/chaoss/wg-common/blob/main/focus-areas/people/contributor-location.md)

To reference this metric in software or publications please use this stable URL: <https://chaoss.community/?p=3468>

<!-- # For groupings in the knowledge base
Context tags: Contributor
Keyword tags: location, geography, IP address
-→
