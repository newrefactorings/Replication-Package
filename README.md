# Replication Package Guide

## Overview
The replication package contains the refactoring containing commits which were extracted from the subject applications (Springframework, Elasticsearch, Kafka, Hadoop, Tomcat, and Junit4). The commit and 
the assocaited refactorings are provided in the apackage. 
This guide provides instructions for cloning and setting up the subject applications, as well as accessing the refactoring-associated commits. Follow the steps below to ensure a successful setup.

## Steps to Setup

1. **Clone the Subject Applications**
   - Clone each of the following repositories to your local machine:
     - **Spring Framework**: [GitHub Repository](https://github.com/spring-projects/spring-framework)
     - **Elasticsearch**: [GitHub Repository](https://github.com/elastic/elasticsearch)
     - **Kafka**: [GitHub Repository](https://github.com/apache/kafka)
     - **Hadoop**: [GitHub Repository](https://github.com/apache/hadoop)
     - **Tomcat**: [GitHub Repository](https://github.com/apache/tomcat)
     - **JUnit 4**: [GitHub Repository](https://github.com/junit-team/junit4)

2. **Download and Unzip the Replication Package**
   - After cloning the repositories, download the replication package and unzip it to access the refactoring-associated commits.

3. **Accessing Refactoring Commits**
   - Navigate to the folder of the desired project using the command line.
   - Use the command `git show <commit>` to view the contents of a specific commit.

### Example: Viewing a Refactoring Commit for Hadoop

1. Open your command line interface.
2. Navigate to the Hadoop project folder:
   ```bash
   cd path/to/hadoop
   git show <commit>
   Replace <commit> with the actual commit hash you wish to inspect.
