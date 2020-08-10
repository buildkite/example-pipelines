# Example Buildkite Pipelines

A list of example repositories for setting up a [Buildkite](https://buildkite.com/) pipeline.

## Languages and Frameworks

- [Bash](https://github.com/buildkite/bash-example) - A simple bash example with artifacts, inline images and shell output
- [Bazel](https://github.com/buildkite/bazel-example) - Building with Bazel on Buildkite
- [Python - pipenv](https://github.com/buildkite/python-pipenv-example) - An example of testing a Python project w/ pipenv
- [Python - Docker](https://github.com/buildkite/python-docker-example) - An example of testing a Python project w/ Docker and pipenv
- [Bash - Parallel](https://github.com/buildkite/bash-parallel-example) - Another simple bash example that runs across multiple agents in parallel
- [Ruby - rbenv](https://github.com/buildkite/ruby-rbenv-example) - An example of testing a Ruby project w/ rbenv
- [Ruby - Docker](https://github.com/buildkite/ruby-docker-example) - An example of testing a Ruby project w/ Docker
- [Rails - Parallel](https://github.com/buildkite/rails-parallel-example) - An example of testing a Rails project in parallel w/ Knapsack
- [Rails - Parallel w/ Docker](https://github.com/buildkite/rails-docker-parallel-example) - An example of testing a Rails project in parallel w/ Knapsack & Docker
- [Node.js](https://github.com/buildkite/nodejs-example) - An example of testing a Node.js project
- [Node.js - Docker](https://github.com/buildkite/nodejs-docker-example) - An example of testing a Node.js project w/ Docker
- [Golang](https://github.com/buildkite/golang-example) - An example of testing a Golang project
- [Golang - Docker](https://github.com/buildkite/golang-docker-example) - An example of testing a Golang project w/ Docker
- [Xcode - Fastlane](https://github.com/buildkite/buildkite-fastlane-demo) - An example of building and testing a Fastlane project
- [Gradle - Docker](https://github.com/buildkite/gradle-docker-example) - An example of building a Gradle project

## Step Types and Techniques

- [RSpec & JUnit Build Annotations](https://github.com/buildkite/rspec-junit-example) - Annotation a build with JUnit test failure information
- [Artifact Uploading and Downloading](https://github.com/buildkite/artifacts-example) - Uploading and downloading artifacts between build pipeline steps
- [Block steps](https://github.com/buildkite/block-step-example) - An example of how to include block steps with form fields in your pipeline
- [Dependent Pipelines](https://github.com/buildkite/dependent-pipeline-example) - Triggering another pipeline from a pipeline
- [Dynamic Pipelines](https://github.com/buildkite/dynamic-pipeline-example) - Generating a pipeline’s steps programatically at run-time
- [Static Site Deployment](https://github.com/buildkite/static-site-deployment-example) - Deploying a static site via rsync with dynamic branch to subdomain mappings

## Third-party tools

- [Jobsworth](https://github.com/saymedia/jobsworth) uses dynamic pipelines for defining high level build and deploy processes

## template.yml files

All of the examples contain a `buildkite/template.yml` file so that you can easily add the project to your Buildkite account using the 'Add to Buildkite' button in the readme. You don't need this file in your own projects.

## Contribute

[File an issue](https://github.com/buildkite/sample-pipelines/issues) or [send a pull request](https://github.com/buildkite/sample-pipelines/pulls) if your favourite tool or framework isn't on the list.
