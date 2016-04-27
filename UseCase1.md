# Use Case 2

* __Title:__
Manager determines policy violations on a package.

* __Primary Actor:__
Manager

* __Goal in Context:__
Examining if a code package meets policy standards, so a project can abide by its policy.

* __Stakeholders:__
Developer/Manager

* __Preconditions:__
The manager is able to get current vulnerability and policy information, and the databases for both are up-to-date.

* __Main Success Scenario:__
Any policy violations the package contains is found, and the package is accepted or denied (based on results.)

* __Failed End Conditions:__
Vulnerability information needed to pass policy is not present for comparison; any information used to determine policy violations isn't accurate.

* __Trigger:__
Package has all vulnerability information gathered.
