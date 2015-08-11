---
title: "Stage 2: Prepare"
---

<div class="highlight-pullout">Preparing data by cleaning and providing context are the most challenging part of the open data life-cycle.</div>

Once data has been identified and prioritized, the agency prepares the data for publication. The data is scrubbed for sensitive & personally identifying information (PII) and described with metadata.

#### Protect PII 

Removing PII data from data can be difficult, particularly for unstructured data. Autoredaction technologies are being used for text-based and unstructured data. However, for tabular or structured data, anonymizing data and blurring (aggregating) objects are the best methods for protecting privacy. The U.S. department of Education has useful guidelines for anonymizing data.

<blockquote>While it may not be possible to remove the disclosure risk completely, de-identification is considered successful when there is no reasonable basis to believe that the remaining information in the records can be used to identify an individual.</blockquote>

One guideline administrators mentioned for structured data was aggregating data points up to units of eleven or more. Meaning, that if a personal identifier has fewer than 11 units, it should be aggregated together at a higher level of grouping. For example, if you are publishing averages of standardized test scores for a school, in order to publish the average by classroom, it should have more than 10 students. Continuing with the example, if the classrooms has ten or fewer students, the scores should be aggregated to a larger grouping, like the grade-level.

<div class="pullquote">
  <div class="quotetext">Protecting sensitive data is job number one for open data.</div>
  <div class="quotesource">Administrator, HHS</div>
</div>

#### Provide Context 

Descriptive metadata makes datasets indexable and usable. Metadata content includes references to a data dictionary to define data elements, descriptions how the data was collected, guides on interpreting the data, and warnings or disclaimers. Publishing data on sites like data.gov necessitate metadata. If you are wondering what to include, Project Open Data maintains a [Common Core Metadata](https://project-open-data.cio.gov/schema/) Schema.

You and your agency should verify that personally identifying information about the data creators is not being released the metadata (File formats such as PDF, Word, and Image files often have detailed, hidden metadata that is automatically generated and attached to the file). Metadata is also a place where you can be transparent about data and its shortcomings or at least provide a resource (i.e., a link) to where you maintain release notes. 
