# DFD Dictionary

### Data Stores

* __CPE Information DB__
> Common platform enumeration score that is provided by NIST and ranks the external source code with a vulnerability score that is stored within the data store for refernce at a later time.

* __Risk DB__
> The risk database stores packages and the CPE information that belongs to the package. All external source packages incoming to the organization are required to be stored in this database.

* __Policy DB__
> All policies within the organization are created and then stored in the Policy Database for reference at any time throughout the project. Policies stored here outline all regulations that must be met in order for the project to meet criteria in order to continue.

* __National Vulnerability Database__
> The National Vulnerability Database is an external database that we use in order to request CPE information on external packages we are considering engaging with. This provides the vulnerabilities and other information that allows us to see if the package meets our rules and regulations.

### Processes

* __Manage CPE Information__
> A process that sends a request to NIST for risks and vulnerabilites on a specific package. This package also receives the information from NIST and creates a file that contains CPE information on the package and sends the file to the CPE Information Database to be stored.

* __Manage Code Streams__
> A process that takes the external file and package from the developer, sends the package to the CPE Information DB, and recieves the corresponding CPE file to that package. It then sends the package and the received CPE information to the Risk database to be stored for eventual use by the manager.

* __Manage Project Source Code__
> A process that the corporate manager can supply with project information whenever is necessary. Whenever new external source is needed for the process, the process will inform the corporate developer of the need. The corporate developer can also request information on the project via this process.

* __Manage Risk Information__
> A process that accepts project information from the corporate manager, and then requests project risk information from the Risk Database. The Risk Database sends back a response with risk information relevant to the requested information. Vulnerability information is then returned back to the corporate manager for other uses. 

* __Manage Policy Information__
> A process that accepts project info from the corporate manager and will then either request policy information, or add new policy information to the Policy Database. When the process requests policy information from the Policy Database, it'll receive a response with the pertinent policy information. The retrieved project policy information will then be returned to the corporate manager.

* __Determine Policy Violations__
> A process that takes in information such as the project information and project policy information and compares the two documents to see if any part of the project is in violation of the policy and returns a file that tells the corporate manager what, if any, part of the project is in violation of the policy.

* __Create Manifest__
>Create manifest is a process that recieves the package and vulnerability information from the coporate manager and creates a manifest file that is then passed back to the coporate manager.

### Data Flows

* __Package:__
A package of useful code--the result of using or retooling external source to meet the needs of the project--that will be used in the project, if no policy violations have occured from the package's vulnerability information.
* __Source file:__
The source code from the external source used in creation of the package.
* __CPE request:__
A request of the CPE score on a package to check for known vulnerabilities.
* __CPE response:__
A response from the National Vulnerability Database with the CPE score of a package.
* __CPE file:__
A file that is created that contains the CPE score from the NIST database along with the package information that the score is related to.
* __Package and CPE info:__
A combination of the package and the CPE information that are to be stored together in the risk database.
* __Project policy info:__
A document containing the policy currently in place for the project.
* __Policy info request:__
A request sent to the policy database in order to recieve the policy information.
* __Project policy info response:__
A response provided to the requester on the current policy information regulating the project.
* __Project info:__
A document containing all the current project information.
* __External source code retrieval request:__
A request made by the corporate manager, informing the developer to retrieve and use more source code (specified by the request.)
* __External source info request:__
A request made by the corporate developer, asking for project information regarding external source (if new external source is needed, or what external source will be used, ect.)
* __CPE Info:__
A document containing the CPE score and other vulnerabilities about a package.
* __Project Risk Request:__
A request made to the Risk Database for the risk information on a package or packages.
* __Project Risk Response:__
A response to the Project risk request by the Risk Database, giving the risk information on a package or packages.
* __Vulnerability Info:__
A document that provides the CPE score along with known risks and vulnerabilities of the package.
* __Manifest File:__
A document that contains the package and vulnerability information along with other necessary information on the package that is in consideration for engagement.
* __Discovered Policy Violations:__
A file containing the comparison of the policy and the current project to show violations and risks that do not meet the guidelines outlined by the policy.

### External Entities
* __Developer:__
The developer is the internal employee that completes tasks within the project and decides what external source could possibly be useful for the task they are attempting to complete. They also submit potential sources for vulnerability information and pass all information gathered along through the company for a final decsion. 

* __Corporate Manager:__
The coporate manager sets policy for the engagement with external source.  They also compare the incoming code and packages to the policy in order to decide if it is acceptable.  They also create the manifest for each package of source code. 
