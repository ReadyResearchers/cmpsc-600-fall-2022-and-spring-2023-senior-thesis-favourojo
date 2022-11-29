# Template description

This repository contains the starter materials for your thesis in Computer
Science 600 and 610 in Fall 2022  and Spring 2023 academic term. The main
directory of this repository contains the Markdown template for a project that
is designed for use with GitHub Classroom. To learn more about the course
in which these assignments were completed, please refer to the `README.md` file.

The template specifies various settings in the `config.yaml` file included in the
repository. Change the appropriate values under the `Project-specific values`
heading. Changing other values outside of that section may cause the project to
fail to build. **Modify these values at your own risk.**

Author your thesis in the `thesis.md` document using appropriate Markdown
hierarchy and syntax; GitHub Actions will automatically create a PDF from the
`abstract.md` and `proposal.md` files. Consult the `README` of the proposal
repository to learn how to properly build and release this PDFs.

## Citations and references

Including references throughout requires a specific pseudo-Markdown tag, demonstrated
in the following blockquote. (Inspect the `thesis.md` file to see the format.)

> A citation, when included correctly, will appear as it does at the end of this
> sentence. [@plaat1996research]

## Labeling figures

To label a figure (i.e. an image), referencing the image using correct Markdown
will automatically caption the figure:

```markdown
![Label](images/IMAGE_NAME.png)
```

## Labeling tables

To provide a label for a table, write a short caption for the table and prefix the caption
with `Table:` as in the example below:

```
Table: A two-row table demonstrating tables

|Row number | Description |
|:----------|:------------|
|1          |Row 1        |
|2          |Row 2        |
```

## Other template information

Two things specific to this template to also keep in mind:

1. It is your responsibility to remove this description section before building
the PDF version you plan to defend.
2. References _will only appear if cited correctly_ in the text

## Note on `LaTeX` commands

Documents may include specific `LaTeX` commands _in Markdown_. To render these, surround the commands
with markup denoting `LaTeX`. For example:

```
Checkmark character:   $\checkmark$
Superscript character: $^{\dag}$
```

If using a special package not included in the template, add the desired `LaTeX`
package or command/macro to the `header-includes` property in [config.yaml](config.yaml).

Should this package not be included in the environment shipped with this template,
you may also need to add the package to the [GitHub Actions Workflow](.github/workflows/main.yml).

Direct any questions about issues to your first reader.

# Introduction

This chapter describes your completed senior thesis work,
including the overall aims  and the background motivating your research. Whenever
possible, you should use one or more concrete examples and technical diagrams.

It is often useful and necessary to separate the introduction into multiple sections.
Several possible sections are proposed below, you can use these or distribute your
introductory text into sections in another way.

The headings below propose _one way_ you might structure this section of the document.

## History of Pittsburgh Displacement
Few places held as much promise for the huge numbers of African Americans fleeing the South in the years following the Civil War as the thriving city of Pittsburgh, Pennsylvania. Black people flocked to Pittsburgh, particularly to the Hill District, hoping to find work in the steel and railroad industries and escape the Jim Crow segregationist laws of the Reconstruction-era South. The Hill District was a neighborhood close to downtown but up against steep hills, making it an unattractive place for the city's upper classes to live. In the Hill District, a city-within-a-city that was acknowledged by the 1930s as the center of black culture and commerce, African Americans established close-knit communities. The Negro League Pittsburgh Crawfords, one of the best baseball teams in the country, played there at Greenlee Field, the first black-owned and black-build baseball stadium in America. It was also home to one of the most active jazz scenes in the nation. However, as the century went on, the neighborhood's decaying infrastructure cast a shadow over it. Regardless of whether the Lower Hill District's structures need restoration, the city decided to demolish them in 1956 to make room for the construction of the new Civic Arena. Over the subsequent five years, this resulted in the eviction of 8,000 inhabitants, further causing overcrowding in the Middle and Upper Hill areas. This led to the loss of much of the city's cultural vitality and significantly changed how the Hill is today. After these event, the city of Pittsburgh, as a whole, suffered through a period of economic decline as the city would start to lose their number of jobs and residents to the suburbs and to overseas. Though they faced hardship, the African-American population in Pittsburgh would continue to grow, reaching to about 12% in 1950. However, that would not stop the rampant unfair employment practices and barriers they would have to overcome to live where they wanted to live. Black unemployment was more than twice as high as white unemployment from the early 1950s to the early 1960s, and wealth disparities were pervasive. Even though the city passed a fair employment practices legislation in 1953, approximately 25% of all discrimination complaint cases across the states were filled with the Pittsburgh area office. 

## SQLite3 
An SQL database engine that is compact, quick, self-contained, highly reliable, and full featured is implemented by the C-language library knows as SQLite. SQLite database files are frequently used as long-term data storage formats and as containers to move rich content between computers. The distinguishing characteristics of SQLite include self-contained, serverless, zero-configuration, and transactional. SQLite being a serverless database engine makes it differ from its counterparts who are client-server based, MySQL and PostgreSQL.

## Data Analysis



## Motivation
In 2018, there were 1,738,057 people living in the Pittsburgh metro area, and there was 2,324,743 people living in the Pittsburgh metro region overall, including people living in rural areas. Statistically, the racial composition of Pittsburgh in the year of 2022 is 66.37% White, 22.98% Black or African American, 5.83% Asian, 0.19% Native American, and 0.95% of other races not listed. Within the semi- diverse community of Pittsburgh, there was a clear displacement between the neighborhoods, whether one 
was speaking about the suburban communities or the urban communities. In both the suburban and urban communities in Pittsburgh, PA, the percentage of white people is more than 82%. Inside these primarily white communities,the black population percentage stands as 9.8%. 

If one would compare these differing communities, the statistics would show how the black and brown communities are economically disadvantaged and more vulnerable to displacement. According to the Pittsburgh Neighborhood Project, the poorest communities tend to be black and brown communities because of the intentional decisions at the federal, state, and local level that has starved these poor communities of investment. 


## Current State of the Art


## Goals of the Project
The goal of this project is to shed light on the effect marginalization has had on the black and brown communities. By doing this, 


## Ethical Implications

This document requires that you discuss the ethical implications of your work -- no
matter how benign you consider the outcome of your project. As several major studies
of ethical issues in computer science assert: _no project is completely value-neutral_.

To assist you in elaborating on these issues, the following areas are topics you might
consider addressing. You do not need to address all of them.

* Information Privacy
* Information Accuracy (e.g. can contain reliability)
* Potential Misuse (e.g. computer crime, unintended consequences)
* Second- or Third-Party Risk (e.g. safety)
* Data Collection Issues (e.g. issues inherent in collecting data)
* Algorithmic or Data Bias
* Potential Power Difference / Social Imbalance / Issues in Equity

In addition, reflect on ways that the above harms can be or are mitigated by your work

# Related work

This chapter includes a broad and detailed review of relevant existing work.
The literature review should provide background and context for the thesis work.
The subsections may be organized in whatever manner seems best suited to the material--
chronological, or by topic, or according to some other criteria
(e.g., primary versus secondary resources).

If ethical issues are central to this work, you should also address historical and
contemporary issues or efforts made to address them.

# Method of approach

This chapter answers the "how" question - how did you complete your project,
including the overall design of your study, details of the algorithms and tools you
have used, etc.  Use technical diagrams, equations, algorithms, and paragraphs of text
to describe the research that you have completed. Be sure to number all figures and
tables and to explicitly refer to them in your text.

This should contain:

* lists
* with points
* and more points
  * possibly subpoints

For those projects whose implications address social or moral issues (i.e. ethical
standards, causes, effects), you will want to use this section to describe how you
actively mitigated or considered these issues.

# Experiments

This chapter describes your experimental set up and evaluation. It should also
produce and describe the results of your study. The section titles below offer
a typical structure used for this chapter.

## Experimental Design

Especially as it pertains to responisble computing, if conducting experiments or
evaluations that involve particular ethical considerations, detail those issues here.

## Evaluation

## Threats to Validity

# Conclusion

Traditionally, this chapter addresses the areas proposed below as sections, although
not necessarily in this order or organized as offered. However, the last section --
"Ethical Implcations" is required for this chapter. See the heading below for more
details.

## Summary of Results

## Future Work

## Future Ethical Implications and Recommendations

Especially as pertains to the public release or use of your software or methods, what
unresolved or special issues remain? What recommendations might you make?

## Conclusions


# References

::: {#refs}
:::
