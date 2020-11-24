# Semantic Release Test Project

[![Semantic Release
Badge](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![GitLab Pipeline
Status](https://gitlab.com/nfriend/semantic-release-test-project/badges/master/pipeline.svg)](https://gitlab.com/nfriend/semantic-release-test-project/-/pipelines/latest)

A project for testing
[semantic-release](https://github.com/semantic-release/semantic-release/).

## Pipeline environment variables

The [GitLab pipeline](.gitlab-ci.yml) relies on a few environment variables:

| Variable name  | Description                                                            |
| -------------- | ---------------------------------------------------------------------- |
| `GITLAB_TOKEN` | The token used by Semantic Release to interact with the GitLab project |
| `NPM_TOKEN`    | The token used by Semantic Release to publish the package to NPM       |
