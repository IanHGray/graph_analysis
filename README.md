Quickstart: Graph Databases in Python
Working with Neo4j and NetworkX

Graph databases are a powerful tool for modeling complex relationships, detecting trends across networks, and querying information in ways simply unachievable with traditional relational databases.

At present, Neo4j is the industry leading graph database engine, utilizing the flexible and intuitive <em>Cypher</em> language to run sophisticated queries. Neo4j excels at storing and interacting with large scale graph databases.

That said, Neo4j is an imperfect product. Its documentation is often disjointed and opaque--particularly if you are looking to connect to a graph via Python or R. Major changes are frequently implemented without updates to the official guides, and most of the information available on StackOverflow or similar sites is out-of-date after recent changes. I love this platform--and am excited about its future--but its current form isn't exactly straightforward.

Neo4j also disappoints as an analysis platform, requiring clunky (and often buggy) commands to run basic algorithms. The recently released Graph Algorithms plugin shows promise, but is currently an inconsistent experience.

To fill in the gaps, I prefer Python's NetworkX module for analysis and the Gephi visualization tool to present results. This is hardly a perfect workflow, but at least its a reliable one.

If you have any questions (or if you find better way of doing this) hit me up at gray.ian.hunter@gmail or on Twitter @IanHGray. I by no means consider myself an expert in graph analysis, but I *do* have a high threshold for pain when it comes to reading documentation.
