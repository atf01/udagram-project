
# Pipeline Introduction
this README is aimed to show in details the rationale behind the pipeline construction and execution

## Technology used to build and execute the pipeline
<img src="https://mms.businesswire.com/media/20210902005166/en/821662/23/circle-logo-horizontal-black_%281%29.jpg" width="200" height="200">
circleCi is a platform that helps in the process of creating a pipeline for continuously integrating newly merged code to the project and then publishing the entire app to
the end users.
we can configure a pipeline simply by creating a config.yml included inside a folder .circleci where circleci can find the config file and in turns execute the pipeline.

### you can find more about circle ci through:
- [Documentation](https://circleci.com/docs/)

## The logical structure of the pipeline contains two main jobs (building and deployment) as depicted in the image below
<img src="https://github.com/atf01/udagram-project/blob/main/docs/CircleCi%20Screens/pipeline.PNG">


