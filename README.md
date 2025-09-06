# TEST CVSS v4.1 calculator

This is an idea for elevating "Privileges Required" to make more of a distinction between between Authenticated vs. Unauthenticated vulnerabilities.

You can see what changes in the scoring by checking out the repo and opening the index.html in your web browser.

For example...

## This is still a 10 with PR:N

CVSS:4.0/AV:N/AC:L/AT:N/PR:N/UI:N/VC:H/VI:H/VA:H/SC:H/SI:H/SA:H

## But PR:L is now a 7.2 instead of a 9.4

CVSS:4.0/AV:N/AC:L/AT:N/PR:L/UI:N/VC:H/VI:H/VA:H/SC:H/SI:H/SA:H

## And PR:H is now a 5.8 instead of a 9.4

CVSS:4.0/AV:N/AC:L/AT:N/PR:H/UI:N/VC:H/VI:H/VA:H/SC:H/SI:H/SA:H
