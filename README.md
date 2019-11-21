# aws-reap-old-instances
Simple playbooks which loop through regions and dates and reap old instances

## Change list of regions or dates
Regions and dates to check for are defined in the variables at the top of the main playbook `reap-old-instances.yml`.

In terms of dates, the string are followed by an asterisk in the AWS filter, so `2017` will putput all machines from 2017, while `2017-08` will only output machines from August 2017.
