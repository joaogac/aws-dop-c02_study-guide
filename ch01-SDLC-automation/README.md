# Chapter 01 - SDLC Automation
----------------------------

## SDLC - Software Development Lifecycle

Components of a CI/CD pipeline  
Version control repository  
pipeline (orchestrator)  
build server  
deployer  

- Key principles
- Automation
- Everything as Code (No manual adjustments)
- Test, test, test
- Consistency
- Integrate Frequently

 > Git is the repository is gonna be used in the exam

# Source control Strategies

## Trunk Based Development (TBD)
All work is done on the master branch
When the code reaches an agreeable state - tag/release it
Pros
- Very small changes
- Continuous code merges
- Increase delivery throughput
Cons
- Many tests

## GitHub Flow
Feature branch development
All work is done on individual branches
Branches merged frequently
Pros
- Master is always releasable
- Short lived branches
Cons
- Master is not always up to date
- Large changes to master

## Git Flow
One of the most extensive ones, but also one of the most popular
Features merge to develop
Release branches
Feature & Hotfix branches
Pros
- Master is always releasable
- Strict control
Cons
- Master is not always up to date
- Large changes to master
- Complicated to enforce

## Environmental Branching
One long-lived branch per environment, like one account per env
Changes all to one branch
Graduate release to production
Pros 
- Each env has its own branch
- Prod is always releasable
Cons
- Prod is not always up to date
- Large changes to Prod
- Multiple merges per release 


AWS CodeCommit

