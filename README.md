# Test Driven Development - Next Bill Date Design in Billing Application

User Stories & Acceptance Criteria:
This document contents all the user stories that are developed as part of Next Bill Date Design.

Problem Statement:


Prerequisite:
	1. Java 8
	2. Eclipse for Java Developers
	3. Junit, Mockito, hamcrest jars in local user home
	4. Knowledge of Test driven development methodology

Sprint Zero: - Setting Up Project & Infrastructure
	1. Create a Java 8 maven project with required dependencies
	2. Add simple test case that tests nothing to make sure classpath is correctly resolved.


UserStory 1:
As a user 
I want to see accurate Next Bill Date in Billing History upon premium bill generation.

Acceptance Criteria:
Given that the user has entity with BillCycle Date as 01/01/2019 , bill mode monthly & 
Billing method as Premium billing.
When the user generates premium bill.
The Next bill date has to be updated as 02/01/2019

Given that the user has entity with BillCycle Date as 01/01/2017 , bill mode annualy & 
Billing method as Premium billing.
When the user generates premium bill.
The Next bill date has to be updated as 01/01/2018

