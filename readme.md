## The Open Water Project

### What is the Open Water Project?
The Open Water Project is an initiative to aggregate and homogenize data about programs designed to bring potable water to communities worldwide. While thousands of these programs exist, there's no central clearinghouse of information about them. The OWP hopes to create a standard, extensible format for storing and retrieving information about those programs, a central datastore for that information, an API for retrieving and storing that information, and a web front-end for accessing it.

### What phase is the Open Water Project in?
The OWP is in its earliest discovery and planning phase - an idea and a possible architecture.

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
