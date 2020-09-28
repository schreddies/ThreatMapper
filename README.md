# ThreatMapper

## Intro
The purpose of this software is to make threat modelling easier and, hopefully, after some introduction, to be served as self-service tool for developers. 

## TMaaS
The usage is quite simple - just pick the type of application, the technology stack and mutiple other things and you will get the couple of questions. Answering to these questions will give you the threat model - of course, quite rought and not polished enought, but really good starter to work with. And the best thing, it can be done by developers and QA's before meeting the security team for inital TM. Or periodcaily to make little changes included into team TM - Threat Modelling as a Service 

## Quick guide
1. Pick the kind/type of application that you would like to threat modelling (is that a verb?), 
2. Pick the tenology stack - language, framework, database, cache, environment etc,
3. You just got you first self-service threat modelling,
4. Fill the generated form of the potentiall mitigation if applied,
5. Do it as frequent as possible, update your model, add new threats, revise.

## Limitations
The problem with that software is that we cannot threat modelling the `bussiness - security` class cases. Let's assume that your application have no problems with security at all. Freshly introduced feature, generation of the profile reports - user can generate report from her/his profile with all information gathered about him. However, the implementation don't colrelate the id of genrated report with the id of the user -  any user can use api to call endpoint for every report generated, with randomly generated uuid as the id(yes, it was that case, yes, it was big company :))
