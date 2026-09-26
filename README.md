# GitHubActions2

Using Variables in GH Actions
=============================

Variables for Single Workflow
-----------------------------
It is define as using the env key in the workflow file. The scope of the custom variable set by this method is limited to the element in which it is defined. You can define variables that are scoped for :
- The entire workflow, by using env at the top level of the workflow file.
- The contents of the job within a workflow
- A specific step within a job.
