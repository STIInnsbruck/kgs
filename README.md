# Building a Knowledge Graph from schema.org annotations (KGS)
 KGC 2020 Tutorial

## Tentative Schedule:
**May 4<sup>th</sup> 2020**  
**Duration:** half day, 9am - 1pm Eastern Standard Time (EST)  
**Location:** [Webinar](https://columbiauniversity.zoom.us/u/atn0QphQ2Join)

More information about the program can be found on [the conference's tutorial program website](https://www.knowledgegraph.tech/the-knowledge-graph-conference-kgc/workshops-and-tutorials/#1580503922536-633f3f10-737b)

## Abstract
Building and hosting a Knowledge Graph requires some effort and a lot of experience in semantic technologies. Turning this Knowledge Graph into a useful resource for problem solving requires even more effort. An important consideration is to provide cost-sensitive methods to build a Knowledge Graph that is a useful resource for various applications: “There are two main goals of Knowledge Graph refinement: (a) adding missing knowledge to the graph, i.e., completion, and (b) identifying wrong information in the graph, i.e. error detection.” [Paulheim, 2017] This tutorial is targeting the process from knowledge creation over knowledge hosting, knowledge curation to knowledge deployment – applied to a Knowledge Graph using schema.org and domain specific extensions of schema.org as an ontology. The tutorial will be based on a book the lecturers co-authored: “Knowledge Graphs – Methodology, Tools and Selected UseCases” [Fensel et al., 2020] and is an extended and adapted version of a tutorial the lecturers gave at [SEMANTICS2019](https://2019.semantics.cc/satellite-events/how-build-knowledge-graph).

## Demo Instructions 

### Duke

#### with Docker (Recommended)
We dockerized the Duke tool for you so you do not have to worry about the dependencies on your system. In order to use the dockerized demo:

* Set-up docker on your computer by following the [instructions](https://docs.docker.com/get-docker/) for your operating system. 
* Clone the [repository](https://github.com/STIInnsbruck/kgs) from GitHub by running `git clone https://github.com/STIInnsbruck/kgs` command.
* Open the command line (terminal) in the `tutorial` folder.
* Run `docker build -t duke . ` This command will use the the default docker file which directly runs the Duke tool with the example RDF document.
* Run `docker run -it duke` to run the container. 
* Use the interactive linking to detect duplicates.
* The results will be shown on your terminal.

> Alternatively, you can use the `docker build -t duke --f=Dockerfile_alt . ` command to build the image that gives you access to the linux shell, so you can play around with the tool more flexibly. If you use this option, you should run the tool as described in the **Java** instructions below.

#### with Java

For this option you would need Java installed on your computer. We have tested it with Java 8, but newer versions should also fine. If you are having issues with the dependencies, please consider running the Docker demo.

* Clone the [repository](https://github.com/STIInnsbruck/kgs) from GitHub by running `git clone https://github.com/STIInnsbruck/kgs` command.
* Open the command line (terminal) in the `tutorial` folder.
* Run `java -jar duke-core-1.3-SNAPSHOT.jar --interactive --linkfile=out.txt config.xml`
* Use interactive linking to detect duplicates.
* View the results saved in `out.txt` in the `tutorial` folder with your favorite text editor.


## Organizers
The presenters are experienced PhD students with several publications in the field. They also actively participate in a industry-funded project, [MindLab](https://mindlab.ai), that aims to build a Knowledge Graph for the tourism domain to be consumed by conversational agents. Moreover, the presenters have teaching experience in the field, especially with courses like Semantic Web and Semantic Web Services.

The organizers are co-authors of the book "Knowledge Graphs - Methodology, Tools and Selected Use Cases" [(Fensel et al., 2020)](https://www.springer.com/de/book/9783030374389).

### Elias Kärle
Semantic Technology Institute Innsbruck  
University Of Innsbruck  
elias[dot]kaerle[at]sti2[dot]at  
[elias.kaerle.com](https://elias.kaerle.com)

Elias Kärle is a senior PhD student at STI Innsbruck. His research is focusing on efficient publication methods for Linked Data, supervised by Univ.-Prof. Dr. Dieter Fensel.

### Umutcan Simsek
Semantic Technology Institute Innsbruck  
University Of Innsbruck  
umutcan[dot]simsek[at]sti2[dot]at  
[umutcan.eu](https://umutcan.eu)

Umutcan Simsek is a senior PhD student at STI Innsbruck. His research is on service-driven goal-oriented dialog systems, supervised by Univ.-Prof. Dr. Dieter Fensel. He has been a part of the research group  for 4 years and worked on several industrial and research projects at both national and EU level. He has (co-) authored several publications, including conference and journal publications as well as a book about topics like web service annotation, Knowledge Graph building based on schema.org annotations and domain-specific verification of semantic annotations. He is also a receiver of the [netidee](https://www.netidee.at/user/1154) grant in 2018 awarded by the Internet Privatstiftung Austria for the most innovative PhD and Master theses in Austria.

## Slides

to be published right after the tutorial
