# hedge-fund-neo4j
A graphical database built with Neo4J to represent several factors that exist in the investment industry/space, and how different 'nodes' in that system are interrelated.
I've included CSV and JSON files that show the total database, all nodes and relationships.
However, it is likely easier to view the PDF I attached to see the graph organized and the queries I ran.

Here is a breakdown of the project. 
- I am representing graphical data that explores the functions of different employees and day-day activites within a hedge fund(more of a value-investing style than purely quantitative).
- The point of graphical databases overall is to use distance between nodes as a way to establish which nodes are more closely related than others, similar to LinkedIn's network feature.
- Some of the nodes showcase inheritance, for example both Bill Ackman and Blackrock are invested in the fund and 'Partners'. However, Bill is a 'Person' object while 'Blackrock' is an Institution.

Since the assignment was all about having people as the names of the nodes, I had their names display on the Node and their actual role be another field.
For simplicity, I am attaching below a guide to what each Node represents.

- David -> Fund Manager
- Stephanie -> Secretary
- Bernard -> Trader
- Thomas -> Risk Management
- Bucky -> Accountant
- Ray -> Quantitative Analyst
- Devon -> Recruiter
- Matt -> HR Manager
- Devon -> Intern
- Chuck -> Analyst
- Richard -> Investor Relations
- JP Morgan -> Partner | Institution
- Goldman Sachs -> Partner | Institution
- Blackrock -> Partner | Institution
- William Ackman -> Partner | Person
- Q1 Call -> Conference Call
- Apple Inc -> Company
- Common Stock -> Common_Stock
- Bonds -> Bonds
- FGC High Risk -> Fund
