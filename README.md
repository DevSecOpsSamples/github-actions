# GitHub Actions

[![Build](https://github.com/DevSecOpsSamples/githubactions/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/DevSecOpsSamples/githubactions/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=DevSecOpsSamples_githubactions&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=DevSecOpsSamples_githubactions) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=DevSecOpsSamples_githubactions&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=DevSecOpsSamples_githubactions)

## Overview

Provides GitHub Workflow and Action samples.

## Sample Repositories

| Repository                          | Workflow File | Actions |
|---|--------------------------------|------|
| gke-workload-identity | [build.yml](https://github.com/DevSecOpsSamples/gke-workload-identity/blob/master/.github/workflows/build.yml)     | [actions](https://github.com/DevSecOpsSamples/gke-workload-identity/actions/workflows/build.yml) | GCP, gcloud, Docker, Terraform, Python, pytest, Sonarqube |
| jenkins-fargate-cdk   | [build.yml](https://github.com/DevSecOpsSamples/jenkins-fargate-cdk/blob/master/.github/workflows/build.yml)     | [actions](https://github.com/DevSecOpsSamples/jenkins-fargate-cdk/actions/workflows/build.yml) | Docker, CDK, Sonarqube |

## Docker

- Build multi-platform docker image files: [docker-buildx-gcr.yml](docker-buildx-gcr.yml)

## Cache

- Optimize build speed using the `cache` plugin: [java/README.md](java/README.md)

    [java/.github/workflows/build-java.yml](java/.github/workflows/build-java.yml)

    [java/.github/workflows/build-java-sonarqube.yml](java/.github/workflows/build-java-sonarqube.yml)

## Matrix

- [gke-workload-identity](https://github.com/DevSecOpsSamples/gke-workload-identity/blob/master/.github/workflows/build.yml)

## Reference

- [GitHub Actions /Using workflows / Cache dependencies / Caching dependencies to speed up workflows](https://docs.github.com/en/actions/using-workflows/caching-dependencies-to-speed-up-workflows#managing-caches)

- https://github.com/actions/cache

- https://github.com/actions/cache/blob/main/examples.md#java---gradle
