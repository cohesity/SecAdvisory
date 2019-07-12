
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
