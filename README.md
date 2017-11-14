# cd_replication
Our reproducibility package (data and scripts) for CD study.

## 1. Survey
  *CD_Survey_questions.pdf:* our questionnaire.
  
## 2. Quantitative study
### A. Data
  #### a. Projects basic information
  *selected_projects_info.csv:* project name, workflow, and #builds. 
  #### b. Builds data
  * *dockerhub_builds_info.csv:* Docker Hub builds
  * *travis_ci_builds_info.csv:* Travis-CI builds
  * *circle_ci_builds_info.csv:* Circle CI builds
  #### c. Dockerfile history data
  *dockerfile_changes_info.csv:* project name, file path, modified date, lines, linter issues, and base image info.
### B. Models
  Data tables and R scripts.
  
  * *Model-1:* Release frequency model
  * *Model-2:* Build results model
  * *Model-3:* Configuration stability model
  * *Model-4:* Build latency model
