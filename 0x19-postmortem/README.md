<p align="center">
<img src="error_webstack.png" width=75% height=75%/>
</p>

## Postmortem Report: Outage on the Web Stack

### Duration of Outage:
<div>
Start Time: 2022-12-01 09:00:00 PST.
</div>
<div>
End Time: 2022-12-01 11:00:00 PST.
</div>


### Impact:
During the 2-hour outage, the web stack was unavailable and users were unable to access the web application. The issue affected 100% of users and they experienced errors while trying to access the web application. The website's homepage displayed an error message and users were unable to access any other pages.

### Root Cause:
The root cause of the outage was a misconfiguration of the server firewall rules. The firewall was blocking all incoming traffic on port 80, which is the default port for HTTP traffic. As a result, users were unable to access the web application.

### Resolution:
The firewall was reconfigured to allow incoming traffic on port 80, which resolved the issue and the web stack was brought back online. The change was tested and validated, and users were able to access the web application without any issues.

### Preventive Measures:
To prevent similar issues from occurring in the future, the following preventive measures have been taken:

* Regular reviews of firewall rules to ensure they are configured correctly
* Documentation of firewall rules to ensure that all changes are documented and tracked
* Providing regular training on firewall configuration and management to the support team

### Conclusion:
The outage was caused by a misconfiguration of the firewall rules, which resulted in the unavailability of the web stack. The issue was resolved by reconfiguring the firewall and the web stack was brought back online. Preventive measures have been put in place to prevent similar issues from occurring in the future.
