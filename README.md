# ThreatMapper

## Intro
The purpose of this software is to make threat modelling easier and, hopefully, after some introduction, to be served as self-service tool for developers. 

## Usage
The usage is quite simple - just pick the type of application, the technology stack and mutiple other things and you will get the couple of questions. Answering to these questions will give you the threat model - of course, quite rought and not polished enought, but really good start to work with. And the best thing, it can be done by developers and QA's before meeting the security team for inital TM. Or periodcaily to make little changes included into team TM. 

## Quick guide
1. Pick the kind/type of application that you would like to threat modelling (is that a verb?), 
2. Pick the tehcnology stack - language, framework, database, cache, environment etc,
3. 

## Limitations
The problem with that software is that we cannot threat modelling the bussiness - security cases. If your application have no problems with security but new feature will introduce the  bypass to proper tenant separation - user can generate report from her/his profile but generated report ID assigend to user id - any system user can use rest api to call this endpoint for every report generated (yes, it was that case, yes, it was big company :))
