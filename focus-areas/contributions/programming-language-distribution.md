# **Programming Language Distribution**

**Question:** What are the different programming languages present in an open-source project(s), and what is the percentage of each language?

## **Overview**
The Programming Language Distribution metric identifies the various programming languages used in a project and the proportion of code written in each language. This gives insight into the technical skills required from contributors and the focus of the project. It also highlights how a project may evolve over time, especially in terms of the languages it relies on.

## **Want to Know More?**

<span markdown="1"><details>
<summary>Click to read more about this metric.</summary>

### **Objectives**
Understanding the distribution of programming languages in a project helps multiple stakeholders:
- **Developers and New Contributors:** It aids newcomers in determining whether a project aligns with their skillset. Developers can use this metric to find projects that heavily use languages they are proficient in, which may support job searches or skill development.
- **Project Management:** Open source program offices (OSPOs) and project managers can use this metric to understand the project's profile, see language trends over time, and assess the skills needed for maintaining and developing the project.
- **Project Evolution:** Over time, a project’s language distribution may shift as the focus changes. For example, a project might be 60% Python and 40% JavaScript in one year, but evolve to have a greater proportion of JavaScript as user interface development grows.
- **Diversity and Inclusion:** Projects that have diverse, inclusive communities may reflect this through their language distribution, accommodating contributors with various language proficiencies.
- **Language Dependency:** The metric can also reveal a prominent language used in a project for which a dependency scanner might not yet be identified.

### **Implementation**
Programming Language Distribution is calculated by analyzing the properties of each file in a repository, specifically its programming language. This metric relies on identifiable language extensions, but if the language is unrecognized (e.g., in the case of newer languages), files may temporarily be classified as "other."

### **Parameters**
- **Number of files:** The total number of files written in each programming language.
- **Lines of code (LOC):** The percentage of lines of code written in each language.
  - The metric can present either the number of files or lines of code as absolute values or percentages.
  - For example, one project may be 60% Python by files and 80% Python by lines of code.

Both parameters help analyze language distribution, but depending on the context, one may be more useful than the other. A simple count of files often suffices for an overview, while lines of code provide more detail, though it can be more difficult to interpret.

### **Filters (Optional)**
- **Time:** Analyze how the language distribution changes over time to see trends.
- **Number of Files:** Show the number of files per language in absolute numbers or as a percentage.

![IMG_5290](https://github.com/user-attachments/assets/fe555d2d-8fe7-47d8-8dc7-969bfce4f5be)


- **Lines of Code:** Display lines of code for each language in either absolute numbers or percentages.

![IMG_5291](https://github.com/user-attachments/assets/9f49814c-b29c-4edc-98bb-980ed6f09090)

### **Visualizations** - None specified

### **Data Collection Strategies**
Programming language distribution can be collected by iterating through the files in a repository and identifying the language of each file by its extension. Libraries, such as the one used by Augur, automate this process. For example, Augur uses [scc](https://github.com/boyter/scc) to calculate language distribution.

Special consideration should be given to certain file types, such as Jupyter Notebooks, where the file extension may obscure the actual language used within the notebook.

</details></span>

## **References**
- [scc - A tool for counting lines of code, files, and more](https://github.com/boyter/scc)

## **Contributors**
- Dawn Foster
- Beth Hancock
- Matt Germonprez
- Elizabeth Barron
- Daniel Izquierdo
- Kevin Lumbard
- Sean Goggins
- Yigakpoa L. Samuel (I)

## **Additional Information**
- To edit this metric, please [submit a Change Request here](https://github.com/chaoss/wg-common/blob/main/focus-areas/contributions/programming-language-distribution.md).  
- To reference this metric in software or publications, please use this stable URL: [https://chaoss.community/?p=3430](https://chaoss.community/?p=3430).

<!-- # For groupings in the knowledge base
 Context tags: Programming Language, 
 Keyword tags: language percent, percent, programming languages
 →
