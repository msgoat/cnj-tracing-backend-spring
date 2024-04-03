# Changelog
All notable changes to `cnj-tracing-backend-spring` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [4.0.0] - 2024-04-03
### Changed
- upgraded Spring Boot to version 3.2.4
- upgraded Java to version 21
- upgraded Maven plugins and dependencies
- consolidated POM with other showcases
- consolidated system tests with other showcases
- commit-stage builds produce Docker images for linux/amd64 and linux/arm64/v8 platforms now
- Docker images use Generational Z garbage collector by default
- consolidated common dependencies
- upgraded common cloudtrain dependencies

## [3.3.0] - 2023-11-09
### Added
- Tagging of git branch
### Changed
- Upgraded to helm-maven-plugin version 5.0.0
- Now a helm chart is packaged and pushed as an artifact during the commit-stage build
- Now the helm chart is pulled before deploying during the integration-test-stage build

## [3.2.0] - 2023-06-09
- upgraded postgres to version 15
- added docker-compose.yml to run the showcase locally

## [3.1.0] - 2023-05-26
### Changed
- upgraded to Spring Boot 3.1.0
- switched from jaeger tracing to micrometer tracing via open telemetry

## [3.0.0] - 2023-05-25
### Changed
- upgraded to Java 17
- upgraded to Spring Boot version 3.0.2
- moved to new CloudTrain kubernetes cluster
- switched to new docker base image cnj-docker-jre17-alpine
- improved ingress management in helm chart with added nginx support
- switched to nginx ingress controller

## [2.1.1] - 2022-11-14
### Added
### Changed
- fixed broken helm configuration of postgres secret

## [2.1.0] - 2022-08-26
### Added
### Changed
- upgraded Spring Boot version to 2.7.1
- consolidated with other showcases
- added changelog.md
- improved README.md
