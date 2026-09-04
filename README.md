# Mentorhub SQA

Software Quality Assurance for Mentorhub

This repo contains cypress testing that can be run against VPN or cloud hosted instances of the MentorHub platform.

Testing is broken down to User Journey and Regression Testing. User Journey testing emulates a user completing a task, from login to logout. Regression Testing contains tests that were submitted as a Proof of Defect. Once that defect has been addressed the test is added to the Regression Suite. 

# API and SPA or just a Repo.
I'm torn about how to implement this.... part of me wants a API to run tests, and a SPA to kick-off runs and report outcomes, but other parts think this is just a repo and we can run the tests with npm commands. 
