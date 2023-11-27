This repository contains a source code for a simple web application

Goal: Whenever a push is done to the main branch or a workflow dispatch, a pipeline run and perform the following task;
--> Perform code analysis with Sonarqube
--> Build artifact with Maven
--> Authenticate into AWS
--> Login to Amazon Elastic Container Registry
--> A docker image is built from the artifact
--> A task definition is used to create a new task

