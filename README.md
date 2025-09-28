# Assessing Data Management

## What I Know

### ER Modeling and Relational Design
One of my strong skills is entity–relationship (ER) modeling. I can map entities, relationships, and attributes effectively, translating business scenarios into logical database structures. I have applied this to case studies such as modeling a retail environment with customers, orders, products, and suppliers. This provided the groundwork for writing SQL queries and enforcing referential integrity.

Beyond the basics, I am comfortable with recognizing cardinality (one-to-one, one-to-many, many-to-many) and resolving many-to-many relationships with associative tables. These skills support clean, auditable, and scalable database design.

### SQL Joins and Query Basics
I am highly proficient in SQL querying, particularly in joins and subqueries. Writing inner, left, and right joins to retrieve business-relevant data has become second nature. For example, in one assignment I combined sales tables with customer demographic data to analyze purchase behavior. The success of this exercise depended on my ability to align keys correctly and troubleshoot missing records.

I also use aggregation functions (`SUM`, `COUNT`, `AVG`) and grouping effectively. These allow me to move beyond raw data retrieval into summarization that supports analytics. Writing queries that combine joins, filters, and grouping has been one of my most valuable transferable skills.

### Data Quality and Governance
A further area of strength is my attention to data quality. I have practiced using validation rules, duplicate detection, and referential integrity checks. One project required identifying inconsistent codes in a customer database where entries had multiple formats (e.g., “TX,” “Texas,” “Tx”). I developed a workflow to standardize entries, which emphasized the importance of governance in maintaining long-term usability.

### ETL Foundations
In the second data management course, I gained experience in extract–transform–load (ETL) processes. I can connect to structured sources, perform basic cleaning operations, and load data into relational tables. For example, I extracted data from CSV, cleaned inconsistent category labels, and loaded the final structure into a SQL database.

---

## Where I Am Weak

### Normalization and Schema Design
Although I can apply first, second, and third normal form, I sometimes struggle with recognizing when denormalization is appropriate. Designing schemas that balance normalization with performance requirements has been challenging. In one assignment, I normalized a dataset into multiple related tables, but my schema made queries unnecessarily complex. I realized that advanced schema design requires both technical rigor and sensitivity to business context — an area I still need to improve.

### Complex ETL Workflows
Handling large or complex transformations in ETL is another weak spot. While I can perform simple cleaning tasks, I have limited experience managing error handling, logging, and recovery for failed loads. In professional settings, ETL pipelines need to account for unexpected file formats, dropped connections, and schema changes.

---

## What I Wish I Knew
- **NoSQL and Semi-Structured Data:** I have little hands-on experience with document stores (e.g., MongoDB), key–value stores, or graph databases. These are increasingly important for unstructured or large-scale applications.  
- **Cloud-based Data Management:** While I understand local SQL and ETL, I have minimal exposure to cloud platforms like AWS RDS, Google BigQuery, or Azure Synapse.

---

## Supporting Work / Knowledge
- **Data Analytics Course 1:** [GitHub Repo](https://github.com/ptphamtx/Data-Mining-2/tree/main)  
- **Data Analytics Course 2:** [GitHub Repo](https://github.com/ptphamtx/Data-Mining-1/tree/main)  
- **DataCamp Courses:**  
  - [Intermediate SQL](https://drive.google.com/file/d/1vQlRXrTc0ic5X6IHJh5bTG5vmFpbxMkx/view?usp=sharing)  
  - [Database Design](https://drive.google.com/file/d/1dnPG_GUmaKG4QQ-DisHnGylxAYnF-T0c/view?usp=sharing)  
  - [Data Warehousing Concepts](https://drive.google.com/file/d/1ZMFyA4UHJpA4eYC3gtVs5lkv4HpEpAPx/view?usp=sharing)  

---

## Summary
I’ve built a solid foundation in data management. I can design basic relational schemas and ER models, write SQL (including joins and aggregations) to answer practical questions, set up simple ETL steps to extract and clean structured data, and apply essential ideas from data governance and quality assurance.  

I’m still developing my understanding of advanced schema design, indexing/optimization, and larger-scale ETL. I’ve seen how data management supports other areas — providing clean, well-structured data for analytics, forming the database layer for application development, and aligning with security through access control and accountability.  

These skills have helped me in past class and practice work (for example, retrieving, cleaning, and standardizing datasets so downstream use and basic audits are more reliable). For my capstone, my aim is to design a workable schema, build straightforward ingestion and cleaning pipelines, document metadata for reproducibility, and show how these pieces connect with analytic and system components.
