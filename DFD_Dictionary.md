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

### Relationships

* __Package:__
* __Source file:__
* __CPE request:__
* __CPE response:__
* __CPE file:__
* __Package and CPE info:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__
* __:__


### Other Definitions
