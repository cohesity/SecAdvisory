
July 2, 2019       FN21

## Man-in-the-middle Vulnerability related to vCenter  [CVE-2019-11242]
 

### Problem Description

A man-in-the-middle vulnerability related to vCenter access was found in Cohesity DataPlatform version 5.x and 6.x prior to 6.1.1c. Cohesity clusters did not verify TLS certificates presented by vCenter. 



### Impact

This vulnerability could expose Cohesity user credentials configured to access vCenter. Exposure is limited to vCenter only environments that have strict TLS certificate requirements.

 

### Resolution

To remediate the vulnerability, Cohesity recommends upgrading to Cohesity DataPlatform 6.1.1e or above. 
Customers currently on release 6.1.1c or above are not vulnerable to this issue and can disregard this notice.



### Additional Information:
Software downloads are available here: http://downloads.cohesity.com
If you have any questions, please reach out to Cohesity Support.

email: support@cohesity.com

#### Vulnerability Type
Missing SSL Certificate Validation

#### Vendor of Product
Cohesity, Inc

#### Affected Product Code Base
Cohesity DataPlatform - Affected versions are Cohesity DataPlatform versions 5.x, 6.x prior to 6.1.1c. This is remediated in versions 6.1.1c and 6.2.

#### Affected Component
vCenter communications.

#### Attack Type
Remote

#### Impact Information Disclosure
True

#### Attack Vectors
To exploit the vulnerability, someone must be able to present the Cohesity cluster with a forged vCenter TLS certificate.

#### Has vendor confirmed or acknowledged the vulnerability?
True

#### Discoverer
Cohesity acknowledges the efforts of Karlsruhe Institute of Technology researcher Thorsten Tuellmann who identified the vulnerability and participated in its responsible disclosure.


