# libSBOLj demo application
This project demonstrates an application of libSBOLj, the Java library for Synthetic Biology Open Language (SBOL), through the construction
of a CRISPR-based repression model. This project has been set up to run in Eclipse with Maven, and should be able to be directly imported and executed if you have these set up. Instructions for setting up Maven in Eclipse and detailed description of construction of the CRISPR-based model are provided in this tutorial: https://github.com/SynBioDex/libSBOLj/blob/develop/docs/tutorials/crisprExample/top.pdf. Detailed libSBOLj information can be found at http://sbolstandard.org/software/libSBOL/java/.

## Contents:
* src/main/java/mySBOLexcamples/crispr:
    * RepressionModel.java: The CRISPR-based repression model built with libSBOLj 2.1.0 API.
*  src/test/java/mySBOLexcamples/crispr:
    * AppTest.java: Automatically created testing file. This file is unmodified after its creation.
* pom.xml: Maven configuration of the project
* README.md: this file

## To import into Eclipse:
Import as a Maven project, either directly from the git repository or first cloning and then importing your local copy.

## To run:
To run normally, execute "RepressionModel.java" as a Java application

In response, you should see an RDF/XML output in your Eclipse's console, and a "RepressionModel.rdf" produced under the "crispr" directory.
	
