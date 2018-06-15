# WorkingWithFiles
This is an app developed in C#. It has to work properly and it will do some basic operations over textfiles and export XML file


The application will lists all words of text files as well as the number of their appearance in
each file. The text files shall be read from a directory that has to be provided as application property.
The processing result shall be reported as JSON document that has to validate against the provided JSON
Schema.

Additional Requirements
The implemented solution shall meet the following requirements:
1. the application must be developed in C#
2. the application shall be built by a build system like "Maven" or "Gradle"
5. the schema validation is not scope of the solution - but will be done on our side
6. as requested by the schema, the name of the processed file as well as its modification date shall be
written to the JSON result file as well.
