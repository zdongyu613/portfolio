---
title: "GenomicKB"
date: 2023-08-28T14:56:10-04:00
draft: false
categories: 
- "Liu Lab"
---
[Check GenomicKB Webapp](https://gkb.dcmb.med.umich.edu/)

# GenomicKB - A graph database of genomes for biologists
## Project Intro
Genomic Knowledge Base (GenomicKB, or GKB) is a database that uses a knowledge graph to consolidate genomic datasets and annotations. GenomicKB integrates data from more than 30 consortia, in which the genomic entities and relationships are represented as diverse nodes and edges with properties.

The original article: https://doi.org/10.1093/nar/gkac957
![concept](img/articles/gkb/concept.png)
## Problems
The GenomicKB team is working on designing new methods other than using the  Neo4j prompt directly for users to access the database. They also plan to redesign the website's information architecture and overall design to make it more intuitive and user-friendly. The goal is to enhance the user experience by ensuring easy navigation and visually appealing interfaces that align with the brand image of GenomicKB.
## Solutions
I have designed three distinct methods for accessing data, catering to different user groups. These include a user-friendly GUI web application, an API for seamless integration, and the option to download the entire database. Additionally, I have improved the web information architecture to ensure easy navigation and access to various functions. Furthermore, I have created a comprehensive documentation library specifically for GenomicKB, providing users with a valuable resource for information and support.

## User Researches
### Interviews
The interviews focused on understanding the research interests of biologists and their experience with technologies such as coding and knowledge graphs. The objective was to identify the pain points that biologists face when searching for key genome information and to understand the differences in search behavior between biologists with strong technology backgrounds and those with more traditional approaches. 

The results revealed that biologists typically have a clear research focus on specific diseases, but struggle to find all the relevant genome information. This finding was supported by insights shared by biologists within our team. It became evident that biology researchers face challenges in identifying the mechanism pathway from genes to diseases. Additionally, it was observed that individuals with strong technology backgrounds prefer coding their queries and results to work with downstream coding functions when accessing a database, while traditional biologists prefer a graphical user interface (GUI). As a result, we decided to design two different access methods for GenomicKB to cater to these different user preferences. 
### Personas
There are two personas were made according to my user interviews. 

The first one, Jefferson, describes traditional biologists. For them, computers are like replacements of typewriters and libraries. The computer is a better typewriter for them while writing articles, and Google is like a library for them to search for references so they don’t have to go to a real library to spend a day finding a specific book or article. Computers do not really change their research method intrinsically.
![GUI user persona](img/articles/gkb/gui-persona.png)

The second persona, Emily, is a typical bioinformatician. Her research style is very different from traditional biologists. She is good at using programming language to analyze large amounts of data and find out conclusions. To be honest, she is more like a data scientist than a biologist.
![API user persona](img/articles/gkb/api-persona.png)

## Designs
### Information Architecture
The Information Architecture (IA) model outlines the user flow when accessing the database searching web app. The primary functions of the IA include a user-friendly GUI for traditional biologists and an API guideline documentation for bioinformaticians. Based on feedback from interviews and colleagues, we have also incorporated a supporting center to assist users in getting started, answering questions, and providing a platform for continuous user feedback.
![IA model](img/articles/gkb/ia-model.png)
Along with the IA, the GenomicKB homepage is redesigned to adapt to the new IA.
![Homepage design](img/articles/gkb/gkb-home.png)

### Supporting Center Wireframe
The supporting center serves as a platform for users to engage in discussions and provide feedback while utilizing apps developed by the lab. The wireframe displayed in the screenshot represents the user profile page, while the design for other pages is currently pending as per the supervisor's directive to prioritize essential functionalities.
![Supporting Center wireframe](img/articles/gkb/supporting-center.png)

### Query & Result Interface
The query interface is specifically designed for users who are new to the system. It features a canvas where users can visually represent their queries using connected nodes and edges. On the right side of the canvas, there is an editor toolbox that allows users to modify the details of each node and edge in their query. At the bottom of the page, there is a log box that displays comprehensive information about the current query and provides helpful suggestions for the next steps users can take.
![Query Interface](img/articles/gkb/query-interface.png)

The search result interface will be simplified, as users will have fewer operations to perform. They can easily check the original query and compare it to the search results using a small window in the corner of the interface. If needed, users can edit the original query by clicking the enlarge button on the query window. Additionally, there is an option to export the complete result for further use, rather than simply browsing it within the interface.
![Result Interface](img/articles/gkb/result-interface.png)

### Prototyping
[Link to Figma Prototype](https://www.figma.com/file/AT4GkQSRRHu2LnCdJ9W6ka/GKB-webapp?type=design&node-id=0%3A1&mode=design&t=nbetH6OlKRU6f6uO-1)
The basic interaction logic was brainstormed and decided by using paper cards. All developers from our team were involved in the paper card lo-fi prototype interaction stage. The Hi-fi prototype of the GenomicKB web app is created using Figma, allowing developers to interact with it and assess the information architecture and some interaction logic. However, the level of detail in the querying interaction is restricted due to the javascript package chosen by the developers in the lab, resulting in that aspect not being included in the Hi-fi prototype.
![Hi-Fi Prototype](img/articles/gkb/hifi-prototype.png)

## Development 
### Project Homepage
In order to enhance the accessibility of the website, the homepage is designed using authentic HTML and CSS, with limited reliance on Javascript. This approach ensures that users can access the website with minimal internet usage and without compromising computer performance.
### Documentation Library
The documentation library for the GenomicKB database is created using the HUGO framework, ensuring it is fast and easy to update. This means that users can always access the most up-to-date information without any delays. The library is hosted on Github and is fully open source. It contains comprehensive details about the data in the GKB database, enabling users to easily cite any data they obtain from it.

Currently, the API documentation is being developed and will be made available online once the backend tasks are completed. As per the University of Michigan's policy, the GKB database is freely accessible for academic use, making it open source. Users are welcome to download the entire database, and the documentation provides a download gateway for this purpose. The gateway page offers a detailed explanation of different data formats and instructions on how to use them after downloading. The database is well-versioned to cater to users' diverse requirements.
![Download Gateway](img/articles/gkb/download-gateway.png)


## Introduction and Tutorial Video
{{< youtube Cnl9RpUDpkQ >}}
The video series aims to offer a comprehensive and user-friendly introduction and tutorial for individuals who are new to GenomicKB. It is designed to help them quickly grasp the concept and begin making effective queries as soon as possible.


