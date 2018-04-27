## Release Version: 0.0.2

BACKWARDS INCOMPATIBILITIES / NOTES:

* N/A

NEW FEATURES:

* The HTTPS listener now supports offloading to HTTP target groups.
(Activated by setting parameter "lb_https_offloading=true")
* Ability to add multiple targets to target groups

IMPROVEMENTS:

* Added the following output values:  
 * lb_name
 * lb_arn
 * lb_arn_suffix
 * lb_dns_name
 * lb_zone_id

BUG FIXES:

* Corrected "lb_security_group_ids" typo in README.md