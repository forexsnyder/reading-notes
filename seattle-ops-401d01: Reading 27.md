Jeff Snyder
10NOV2020


From Windows to Splunk

The most efficient way to get data from Windows to Splunk is through the Universal Forwarder.  

Forwarders VS WMI

Forwarders offer the most data types.  WMI doesn’t work well with splunk apps.  Also, WMI uses a method of access that is insecure.

Correct Windows user for Splunk.  The user Splunk installs as determines the level of access to events being monitored.

Installation options.

Best practice to install with little need to configure post-installation.  Windows installations offer a UI.


from "https://lantern.splunk.com/hc/en-us/articles/360043721173-Getting-data-into-Splunk-from-Windows-endpoints"
