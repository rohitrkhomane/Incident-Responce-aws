# Incident-Responce-aws

This script uses the aws CLI to get all CloudTrail events and the jq tool to filter the events. 
The script identifies compromised AWS Buckets, IAM Users, and other indicators of compromise (in this case, changes to the bucket policy) by filtering on the EventName field.

Note: 
This script is just an example and is not intended to be a comprehensive incident response plan.
The specific events and filters used here should be adjusted based on your own use case and threat landscape.
