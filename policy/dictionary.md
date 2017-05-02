
Developer : The corporate developer who writes software code. The developer submits the software package to the Manage Software Information process that returns vulnerability and open source software license results back to the developer. The developer can request results form the internal database. The developer follows the corporate policy when writing software code.

Manager: The corporate manager reviews the results of the vulnerability and open source software license scans against corporate policies. The manage updates the policies according to organizational and project goals.

Manage Software Information: The main process that handles submiting the software package to the open source scanner for licenses, and queries NIST for any software vulnerabilities. The process sends the results back to the developer and stores the results in an internal database for future review.

NIST Database: The database is an external database ran by the National Institute of Standards and Technology. From the NVD website: "NVD is the U.S. government repository of standards based vulnerability management data represented using the Security Content Automation Protocol (SCAP). This data enables automation of vulnerability management, security measurement, and compliance. NVD includes databases of security checklists, security related software flaws, misconfigurations, product names, and impact metrics." (https://nvd.nist.gov/)

Scan for OSS Component: Process scans the software package for any known open source license agreements and sends the results back to the Manage Software Information process.

Policy Database: An internal database that contains current and outdated policy statements created and maintained by the manager. 

License and Vulnerability Database: An internal database that contains open source software licenses and vulnerability results from the Manage Software Information process. The results from the database can be accessed by the developer and the manager.
