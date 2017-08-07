# Monorepo

Create a pipeline `monorepo` for this repository with a pipelien upload step and webhooks for new commits. Also create a pipeline `monorepo-a` to run builds in `a/` and `monorepo-b` to run builds in `b/` against this repository, but without webhooks. The root `monorepo` pipeline will trigger a build for each commit for both `monorepo-a` and `monorepo-b` which can run their own pipelines, and which will run in their subdirectories.

Changing this monorepo pipeline into a [dynamic pipeline](https://buildkite.com/docs/pipelines/defining-steps#dynamic-pipelines) would enable using the [builds REST API](https://buildkite.com/docs/rest-api/builds) to find the last build commit for this branch, then using a git diff would allow only triggering builds for the affected subdirectories.
