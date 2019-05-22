# splunk_concurrency_helper
Searches and dashboards to assist with optimising concurrency settings

Using rest scripts:
-Run the search interactively.
-Adjust any search creteria or eval statements as needed
-Copy the change_script field in the output to a file on a search head or other host that has access to the REST endpoint of your search head
-Adjust URL and password as needed, or parameterise.
-Run as a shell script
-Follow the same steps using the rollback_script to roll back changes
-Rest calls have an immediate effect, replicates between cluster members, and do not require a reboot.
