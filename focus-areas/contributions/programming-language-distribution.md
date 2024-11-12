# Programming Language Distribution

**Question:** What are the different programming languages present in an open-source project(s), and what is the percentage of each language?

## Overview
The Programming Language Distribution metric identifies the various programming languages used in a project and the proportion of code written in each language. This gives insight into the technical skills required from contributors and the focus of the project. It highlights how a project evolves, especially in terms of the languages it relies on. 

This metric helps multiple stakeholders:
- **Developers and New Contributors:** It aids newcomers in determining whether a project aligns with their skillset. Developers can use this metric to find projects that heavily use languages they are proficient in, which may support job searches or skill development.
- **Project Management:** Open source program offices (OSPOs) and project managers can use this metric to understand the project, see language trends over time, and assess the skills needed for maintaining and developing the project.
- **Project Evolution:** Over time, a project’s language distribution may shift as the focus changes. Example, a project might be X% Python and Y% JavaScript in one year, but evolve to have a greater proportion of JavaScript as user interface development grows.
- **Diversity and Inclusion:** Projects that have diverse, inclusive communities may reflect this through their language distribution, accommodating contributors with various language proficiencies.

## Want to Know More?

<span markdown="1"><details>
<summary>Click to read more about this metric.</summary>

### Data Collection Strategies
Programming language distribution can be collected by iterating through the files in a repository and identifying the language of each file by its extension. This metric relies on identifiable language extensions, but if the language is unrecognized (e.g., in the case of newer languages), files may temporarily be classified as "other." Libraries, such as the one used by Augur, automate this process. For example, Augur uses [scc](https://github.com/boyter/scc) to calculate language distribution.

Special consideration should be given to certain file types, such as Jupyter Notebooks, where the file extension may obscure the actual language used within the notebook.

* Parameters
  - **Number of files:** The total number of files written in each programming language.
  - **Lines of code (LOC):** The percentage of lines of code written in each language.
    - The metric can present either the number of files or lines of code as absolute values or percentages.
    - For example, one project may be X% Python by files and Y% Python by lines of code.

Both parameters help analyze language distribution, but depending on the context, one may be more useful than the other. A simple count of files often suffices for an overview, while lines of code provide more detail, though it can be more difficult to interpret.

### Filters

 - Time
 - Number of Files - The number of files of each language.

	![Number of Files Table](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/contributions/images/language-distribution_number-of-files-table.png)

 - Lines of Code - The percentage of lines of code for each language.

	![Number of Files Table](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/contributions/images/language-distribution_lines-of-code-table.png)


Either lines of code, or files, could be presented as absolute numbers, or percentages, depending on the application of the metric. In many cases, a simple count of files is useful, while the absolute number of lines of code can be difficult to differentiate because the numbers are much larger.

### Visualizations 
- None specified

</details></span><br>

## References
- [scc - A tool for counting lines of code, files, and more](https://github.com/boyter/scc)

## Contributors
- Dawn Foster
- Beth Hancock
- Matt Germonprez
- Elizabeth Barron
- Daniel Izquierdo
- Kevin Lumbard
- Sean Goggins
- Yigakpoa L. Samuel (I)

## Additional Information
- To edit this metric, please [submit a Change Request here](https://github.com/chaoss/wg-metrics-development/blob/main/focus-areas/contributions/programming-language-distribution.md).  
- To reference this metric in software or publications, please use this stable URL: [https://chaoss.community/?p=3430](https://chaoss.community/?p=3430).

<!-- # For groupings in the knowledge base
 Context tags: Programming Language, 
 Keyword tags: language percent, percent, programming languages
 -->
