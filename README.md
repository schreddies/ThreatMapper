# ThreatMapper

## Intro
The purpose of this software is to make threat modelling easier and, hopefully, after some introduction, to be served as self-service tool for developers. 

## Intro part II
We strongly believe that the application security is the process. Not something that you can achieve with one penetration test nor with the beautiful documentation. Especially in the modern days, with continous deployment where the applications are changing each day. Each hour is even more accurate. The Security Development Lifecycle (SDL) is infested with mutiple processes but our most favourite of them all is the Threat Modelling.

## TMaaS
The usage is quite simple - just pick the type of application, the technology stack and you will get the couple of questions. Answering to these questions gives you the threat model - of course, quite rought and not polished enought, but really good starting point to work with. The best thing, it can be done by the teams before meeting the security team for inital TM. Or periodcaily to make little changes included into product Threat Modelling. In other words: Threat Modelling as a Service 
![tm](https://github.com/schreddies/ThreatMapper/blob/master/Blank%20Diagram.png "tm")

## Quick guide
1. Pick the kind/type of application that you would like to threat model (is that a verb?), 
2. Pick the technology stack - language, framework, database, cache, environment etc,
3. You just got you first self-service threat modelling,
4. Fill the generated form of the potentiall mitigation if threat is applied,
5. Do it as frequent as possible, update your model, add new threats, revise.

## Limitations
We cannot guarantee that this software will adress all the things that ca go wrong with your application. As this software is quite new, there is a chance that we don't support the technology you would like to use. In that scenario, please contact us, we will figure it out!
