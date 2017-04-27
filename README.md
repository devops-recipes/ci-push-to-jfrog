# Continuous Integration for a Node JS application with upload of artifacts to JFrog

[![Run Status](https://api.shippable.com/projects/5901b124cd251706003517fe/badge?branch=master)](https://app.shippable.com/github/himanshu0503/ci-push-to-jfrog) [![Coverage Badge](https://api.shippable.com/projects/5901b124cd251706003517fe/coverageBadge?branch=master)](https://app.shippable.com/github/himanshu0503/ci-push-to-jfrog)

![AyeAye](https://github.com/devops-recipes/ci-push-to-jfrog/blob/master/public/resources/images/captain.png)

A simple Node JS application with unit tests and coverage reports using mocha
and istanbul. After completing CI it pushes the artifacts to jfrog.

## Run CI for this repo on Shippable
* Fork this repo into your local repo
* Login into the [Continuous Integration Service](https://app.shippable.com)
* All CI configuration is in `shippable.yml`
* Follow these [CI Setup Instructions](http://docs.shippable.com/ci/runFirstBuild/) if you have never used Shippable CI Service
* Update the integrationName in the integration.hub section if you used something other than `jfrog-integration`
* Change the TARGET_DIR to the directory where you want to store the artifact
* You should be able to run a manual build or webhook build on commit

## CI Reports on Shippable

### CI Integration View
![CI Integration View](https://github.com/devops-recipes/ci-push-to-jfrog/blob/master/public/resources/images/integration.png)

### CI Console Output
![CI Console Output](https://github.com/devops-recipes/ci-push-to-jfrog/blob/master/public/resources/images/console.png)
