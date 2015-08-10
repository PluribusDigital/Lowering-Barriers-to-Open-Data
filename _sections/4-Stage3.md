---
title: Stage 3 - Publish
---

<div class="highlight-pullout">Publishing data is often the most technical aspect of the lifecycle, but also the fastest changing.</div>

Compared to some of the policy and data security issues that agencies face, publishing the data is less formidable. At the same time, administrators recognize that technology is fast moving and keeping up with the most desirable formats and reliable hosting solutions are important for achieving The White House’s order to make "data easy to find, accessible, and usable."

#### Formatting data. 

Formatting data, while not technically daunting, impacts how easy a dataset is to deliver, how popular a data set will be, and how useful it is to its audience. The current format of choice for developers is increasingly JSON. JSON is a format that is easily readable and supports hierarchy. XML has broad support for developers and is readable in analysis programs like Excel but results in larger files.

Currently, spreadsheets do not easily support JSON files without additional conversion steps. If spreadsheets or other analytical tools are likely user’s predominate tool, CSV files (comma separated value) or XML may be the best format to publish. Spreadsheet programs like Excel easily save CSV and XML formatted data. Likewise, CSV files are easy to import into Excel. CSVs can sometimes be more difficult for developers to parse automatically given the wide variation in implementation. Also, CSV files do not support hierarchical data. A well-designed API will make data available in multiple formats per user preference.

Also, different domains use different software. For example, much economic analysis is built on a proprietary tool named Stata. Health sciences often use SAS or R, the former being proprietary and the later being open source. Each program will read CSV and sometimes JSON but also have their own proprietary data formats. 

#### Publishing an API. 

Application programming interfaces (APIs) are how developers access the data and integrate it into new applications. Representational State Transfer (REST) APIs or RESTful APIs are the most common type of API today. RESTful APIs have generally overtaken other standards like SOAP.

Well-designed APIs provide documentation for developers. There are several free tools to create API documentation, such as Swagger. The White House also publishes guidelines for creating, maintaining and documenting APIs.

#### Hosting data.

Many agencies have their own infrastructure for hosting datasets. Other options exist for open, non-classified data. Amazon Web Services is one of the most common data hosts but other IT firms also provide solutions (Windows Azure Storage and Google Cloud Storage). A price war is ongoing and could make hosted options more attractive than just a few years ago. These simple storage services can provide hosting for simple storage of raw, structured and unstructured data.

To provide a data portal for data owners to manage, store and host data there are open source and proprietary options. CKAN (Comprehensive Knowledge Archive Network) is an open source package that often marries with a content management system like Wordpress or Drupal (see also DKAN). CKAN is used for data.gov.

You can run CKAN on your own servers or even in cloud based hosts like Microsoft Azure and Amazon EC2. Companies like Socrata also offer data portal products that go beyond simple data storage and offer end-to-end solution which allow users to browse data hosted by your agency and also have some charting and analysis functions.
