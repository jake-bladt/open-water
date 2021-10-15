## The Open Water Project

### What is the Open Water Project?
The Open Water Project is an initiative to aggregate and homogenize data about programs designed to bring potable water to communities worldwide. While thousands of these programs exist, there's no central clearinghouse of information about them. The OWP hopes to create a standard, extensible format for storing and retrieving information about those programs, a central datastore for that information, an API for retrieving and storing that information, and a web front-end for accessing it.

### The scope of the problem.
[According to the United Nations](http://www.un.org/millenniumgoals/pdf/MDG%20Report%202012.pdf), there are 783 million people worldwide with no access to a reliable, sanitary source of potable water. In addition to the danger of dehydration, communities without potable water struggle with basic hygiene and water-borne disease. A lack of clean water can cause crop loss leading to hunger. Even communities with difficult access to clean water can suffer when their most able members have to take up large parts of their day ferrying back and forth to the water source.

In spite of its size and scope, this is a largely tractable problem. In the twenty years from 1990 to 2010, the worldwide population without reliable, sanitary, potable water dropped from 24% to 11% and continues to drop thanks in large part to programs like the ones the OWP is designed to track. Organizations are already doing good work in this arena and helping them coordinate their efforts could improve millions of lives.

### What phase is the Open Water Project in?
The OWP is in its first development and long-term planning phase. The goal of this phase is to create a website, newsletter, and API that aggregate water-related news for dissemination. These products will ideally be used to fund future development.

At the same time, we are reaching out to existing organizations in the clean and potable water space to determine what needs this project can fill going forward.

### Discovery
The discovery process involves collecting as many sources of data about potable water programs as possible, determining the most reliable protocols for retrieving them properly, and assessing the scriptability of extracting salient details from them.

### A Possible Architecture
A general architecture for data homogenization includes:
* A central datastore for holding both the original documents retrieved and a representation of those documents in the standard, extensible format.
* A collection of collectors that can retrieve source documents reliably.
* A means of describing transformations that output data in the standard format given an input of structured and semi-structured documents.
* A means of retrieving the standardized information.

Additionally, the Open Water Project requires:
* Internationalization and localization
* An API for querying the data
* A web front end for reporting the data
* An administrative front end for transcribing data that is resistant to automated collection or transformation
* An administrative front end for curating collected and transcribed data
* An analyzer for evaluating efficacy of potential water projects

### Australia
Australia's management of the Millenium Drought (1997-2012) is well worth studying. There's a summary [here](https://pacinst.org/wp-content/uploads/2016/02/Managing-Drought-Report-2016-02-23-FINAL-US-Letter.pdf).
