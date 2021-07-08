# Programming Language Distribution

### This metric is a release candidate. To comment on this metric please see Issue #[put the respective Issue Number here]. Following a comment period, this metric will be included in the next regular release.

Question: What are the different programming languages present in an open source project(s), and what is the percentage of each language? 

## Description
The number of programming languages and the percentage of each language in a project provides some understanding of the skills required from code contributors, as well as the nature of the project itself. 

## Objectives
This metric will aid newcomers to a  particular open source project, as well as provide open source program managers with a perspective on the project’s profile, in the context of their own experience and organization. 
In Value: This metric may be used by developers for identifying projects that rely heavily on languages they use, as part of a job search. 

In Evolution: This metric can be useful for identifying changes in the number of files, or lines of code in each language over time. For example, a project may be X% Python, and Y% Javascript at a point in time. Perhaps a year later, the amount of Javascript measured by files, or lines of code, may be greater as a result of a project’s shift in focus toward user experience. 

In Risk: This metric can be combined with dependency metrics to determine if there is a prominent language used in a project, but for which a dependency scanner is not yet identified. 

In DEI: When inclusive, diverse, and equitable communities are identified, they will have some degree of language distribution. 

As an individual looks for new projects to work on, knowing which projects rely on languages they already know, or want to learn, can be one of a number of “personal filters”. 

In general, this metric is useful for OSPOs, and community managers aiming to understand which languages are most prominent, and perhaps which languages are little used, but critical. 

## Implementation
Language distribution takes into account different properties of each file in a repository with an a priori identifiable computer programming language. As new languages emerge, there may be initial periods where counting tools do not recognize their extensions, in which case they may be counted as “other”. Such periods are typically brief.  

### Filters
 - Time
 - Number of Files - The number of files of each language. 

	| **Programming Language** | **Language Files** |
	| ------------ | ----------- |
	| Python | 246 |
	| JSON | 28 | 
	| BASH | 26 | 
	| Plain Text | 14 |
	| Shell | 12 | 
	| gitignore | 8 |
	| YAML | 6 |
	| Makefile | 4 | 
	| R | 2 |
	| Docker ignore | 2 | 
	| Dockerfile | 2 |
	| Markdown | 2 | 

 - Lines of Code - The percentage of lines of code for each language. 

	| **Language** | **Percentage of LOC** |
	| ------------ | ----------- |
	| Python | 94.60% |
	| BASH | 2.48% |
	| Shell | 1.08% |
	| JSON | 0.52% |
	| R | 0.42% |
	| Plain Text | 0.38% |
	| Makefile | 0.16% |
	| YAML | 0.15% |
	| gitignore | 0.12% |
	| Dockerfile | 0.05% |
	| Docker ignore | 0.03% | 
	| Markdown | 0.00% | 


Either lines of code, or files, could be presented as absolute numbers, or percentages, depending on the application of the metric. In many cases, a simple count of files is useful, while the absolute number of lines of code can be difficult to differentiate because the numbers are much larger. 


### Tools Providing the Metric

The [Augur-Community-Reports](https://github.com/chaoss/augur-community-reports) repository provides this metric currently
[GrimoireLab](https://github.com/chaoss/grimoirelab) provides this information through the proxy of file extensions
[Augur](https://github.com/chaoss/augur) provides this information in its frontend, as well as through an API endpoint. 

### Data Collection Strategies
The contents of a repository can be counted by iterating through each file, though several libraries exist, including the one used by Augur: https://github.com/boyter/scc 

File extensions for some languages, like Jupyter Notebooks, might be excluded because they obscure the actual language used.

## References
 - https://github.com/boyter/scc  

## Contributors

 - Dawn Foster
 - Beth Hancock
 - Matt Germonprez
 - Elizabeth Barron
 - Daniel Izquierdo
 - Kevin Lumbard 
 - Sean Goggins 
