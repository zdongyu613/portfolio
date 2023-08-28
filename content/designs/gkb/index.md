---
title: "GenomicKB"
date: 2023-08-28T14:56:10-04:00
draft: false
categories: 
- "Liu Lab"
---
[GenomicKB Webapp](https://gkb.dcmb.med.umich.edu/)

## Knowledge Graph
A Knowledge Graph is a machine-readable format used to organize and represent information. It connects real-world concepts and their relationships to link and integrate data from diverse sources.
Knowledge Graphs are good at data integration with flexibility and scalability, supporting reasoning and inference, and facilitating machine learning and AI.

## GenomicKB
GenomicKB is a specialized Knowledge Graph that consolidates genomic data from over 30 consortia and portals, comprising 347 million genomic entities, 1.36 billion relations, and 3.9 billion entity and relation properties. It focuses on the human genome, epigenome, transcriptome, and 4D nucleome, and provides a coding-free and intuitive query system to turn multi-modal data analysis into a simple process.

## Search GUI Design
### To start a query
To explore GenomicKB, let's look at a simple query. Suppose you want to know which sequence variants are located in the CTCF gene.

First, you need to add two nodes for the two concepts: a sequence variant and a gene by clicking “Add Node”, selecting “sequence variant”, and confirming, you successfully added the first node. In the same way, add another node for the gene. You can add restrictions to the node properties, such as specifying that the gene's name must be "CTCF".

Next, specify the relationship between the two entities. By clicking “Add Edge”, clicking the start node, and dragging your mouse to the end node, you finished adding the edge. The edge type must be selected on the left panel, such as "locate in." Some edge types also support property restrictions.

After creating the query, click "submit," and GenomicKB will guide you to the result page.

### Result page
The results are sub-graphs from the knowledge graph that match your query patterns. You can move the nodes by clicking and dragging, except for nodes of genomic regions. You can also click a node to display its detailed information on the right panel.

Sometimes, the entire query result includes millions of nodes and edges and takes minutes to export. Therefore, the result page only displays the first 5 to 20 matched patterns with a smaller sub-graph to ensure query speed. However, you can always download the complete result by clicking "Export" and leaving your email address for receiving the results. Your email address will not be recorded in our system.

### Complex query
There are some additional functions on the query engine. For example, when clicking on a node, there is some hint information in the “Quick Add” panel showing the potential next node and relationship to add. You can use them to quickly construct the query. When you want to delete a node or an edge, click it, and then use “Delete Selected” to remove it. With all these functions, you can create more complex and biologically meaningful queries, such as the 4th example on the homepage. During this process, you can always refer to our documentation to check all node types and edge types we currently support.


