# Use Case 1

* __Title:__
Developer commits code to be examined for vulnerabilities.

* __Primary Actor:__
Developer

* __Goal in Context:__
Gather vulnerability information for all external source code that is used by developers.

* __Stakeholders:__
Developer / Manager

* __Preconditions:__
Developer is able to check in external source code to vulnerability system. NIST vulnerability database is up to date.

* __Main Success Scenario:__
Developer checks in code and vulnerability information is recorded to the Risk DB.

* __Failed End Conditions:__
Developer is unable to check in code. Checked in code is not checked for vulnerabilities, failing to update Risk DB.

* __Trigger:__
Code check in 
