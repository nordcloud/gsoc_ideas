# Infrastructure as Code Knowledge-base 

## Description

All the major cloud providers (GCP, AWS, Azure) provides ways to utilize
Infrastructure as Code concept in their environment. There are other third-part
solutions like Terraform that aims for the same functionality.

Infrastructure as Code is not getting popular anymore but definitely became an
industry standard used in not only cloud but on-orem environments.

During the years we write billion lines of code for different use-cases and
store them on gists or private repos. Not speaking about huge organizations
where it is possibly that two people on the other side of the planet implements
the same functionality.

This idea is about trying to solve this problem via implementing an application
that supports sharing, maintaining, searching of these templates and the
possibility of deploying these to various cloud providers.

# Example
https://github.com/wooey/Wooey

## Pre-requisites

* General understanding of at least one the major cloud providers
* Familiar with at least one programming language preferably python, node.js, go or rust

## Tasks

* Research which commercial and free open-source alternatives there are.
* Create a data model that can be used by all three cloud providers and fits the requirements
* Create a stateless webapp that implements the basic requirements

## Requirements

* The application must be able to manage users who can create/upload templates
* The application must be able to import different sources for templates (like
  git, s3, etc...)
* The model must be searchable by tags for specific templates
* The application must check validity of these templates by default
* The application must be able to deploy a specified template to one of the
  cloud providers.
* The application should be able to handle blueprints that are a collection of
  templates.
* The application should be able to generate templates based on different
  parameterization to make them generic.
* Would be nice to have linting on the uploaded templates 
* Would be nice if it supported more then one cloud provider
