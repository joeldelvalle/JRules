# jRules Framework

## Introduction
JRules is a framework to execute rules or a group of rules before specific call method. The main developments objetive is validate signature method’s parameters in an easy and simple way, using annotations.

In this first version, jRules is based on spring, for this reason all the annotation's interception happen when the method's calls are through the context. I'm working in other version without spring dependency, using just aspectj.

## Current features
* Create a rule, and execute this rule before method's call.
* Create a few rules, and execute individually before method's call.
* Create a rule and assign one or more groups.
* Associate a list of rules to the same group, and execute this group before method's call.
* Execute a group or more groups of rules before  method's call..
* Execute individually rules and a list of groups of rules before method's call.

## How use it?
Use jRules is very easy!  You just need to follow these four steps.
1. Obtain jRules jar for your project, import the project from maven repository or clone the src and compile the project using maven
2. Configure project's web.xml file
3. Create a jRules
4. Annotate with jRules annotation the method to test

[WikiPage](https://github.com/joeldelvalle/jRules/wiki)
