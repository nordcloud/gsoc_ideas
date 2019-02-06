# AWS/Azure/GCP Janitor

## Description

When using AWS, GCP or Azure in Development and Production sometimes you end up with a lot of resources which you don't know if they are needed or not. Take for example Route53 Recordsets it's not always clear which ones are being used and which ones are not. With this tool it is possible to list unused resources and mark them for deletion to save costs. 

## Pre-requisites

* General understanding of at least one the major cloud providers
* Familiar with at least one programming language preferably python, node.js, go or rust

## Tasks

* Research which commercial and free open-source alternatives there are.
* Create a data model that can be used by all three cloud providers and fits the requirements
* Create a list of resources that are good candidates for the Janitor tool

## Requirements

* Must be able to detect unused resources (For AWS: Trusted advisor plus extra: ECR dockers, Route53, EBS, EIP)
* Must be able to remove unused resources
* Must be able to be used through a CLI
* Would be nice to have a front-end
* Would be nice if it supported more then one cloud provider