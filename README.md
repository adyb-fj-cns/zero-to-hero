# Zero to Hero
Zero to Hero is a set of basic (opinionated) guides on various aspects of modern development. Subjects to be included are simple Getting Started guides for
* Creating pipleines
* Creating microservices

## Introduction
This guide serves mainly as a getting started guide and will provide various links out to other guides/examples.

## Creating pipelines

### Intro
Typical pipelines includes the following elements
* Building
* Testing
* Packaging
* Security scanning (Static/Dynamic)
* Deploying

### CI/CD Systems
A range of CI/CD systems are available via Cloud Vendors, CI/CD SaaS Vendors, Self hosted

#### Cloud Vendors
* AWS CodePipeline
* Azure DevOps

#### Full Systems
* GitLabs
* Jenkins

#### SaaS
* Travis
* CircleCI
* Buddy
* Codefresh
* Codeship

##### Travis
* https://travis-ci.com

##### CircleCI
* https://circleci.com

##### Buddy
* https://app.buddy.works

##### Codefresh
* https://g.codefresh.io/welcome

##### Codeship
* https://app.codeship.com/home

#### Self hosted
* Drone
* Concource
* Go
* Buildbot

##### Drone

* https://drone.io/
* https://docs.drone.io/

##### Concource

* https://concourse-ci.org/

##### Go

* https://www.gocd.org/

##### Buildbot

* https://buildbot.net/
* http://docs.buildbot.net/current/tutorial/

### Security
* Clair
* Aqua Trivy
* Aqua Microscanner
* Aqua Kube Bench
* Aqua Docker Bench
* Aqua Kube Hunter

Links
* https://docs.gitlab.com/ee/user/application_security/container_scanning/
* https://gitlab.com/gitlab-org/gitlab/-/tree/master/lib/gitlab/ci/templates/Security
* https://gitlab.com/gitlab-org/security-products/dast
* https://gitlab.com/gitlab-org/security-products/analyzers

#### Clair

##### Clair scanning

* https://medium.com/paloit/coreos-clair-part-2-installation-integration-558ec664cece
* https://github.com/quay/clair/tree/release-2.0/contrib/k8s
* https://github.com/quay/clair/tree/release-2.0
* https://github.com/arminc/clair-local-scan
* https://github.com/jgsqware/clairctl
* https://medium.com/paloit/coreos-clair-part-2-installation-integration-558ec664cece

##### klar cli tool
* https://github.com/optiopay/klar


#### Aqua Trivy
* https://github.com/aquasecurity/trivy
* https://github.com/aquasecurity/trivy#continuous-integration-ci

#### Aqua Microscanner
* https://github.com/aquasecurity/microscanner

#### Aqua Kube Bench
* https://github.com/aquasecurity/kube-bench

#### Aqua Kube Hunter
* https://github.com/aquasecurity/kube-hunter

### Testing
* Unit testing
* Integration testing
* Smoke testing
* Infrastructure provisioning testing

#### Infrastructure provisioning testing
* Test Kitchen + Terraform + InSpec

## Creating microservices
TODO!

Docker Links
* https://github.com/docker/awesome-compose
* https://github.com/dotnet-architecture/eShopOnContainers

### Testing




#### Functional Testing:

* Unit Testing (required)
* Integration Testing (required)
* Smoke Testing
* Regression Testing (required)
* Sanity Testing
* Acceptance Testing
* End to End Testing (required)

#### Non-functional Testing:

* Performance Testing
* Load Testing
* Stress Testing
* Security Testing (required)
* Compliance Testing
* Usability Testing


