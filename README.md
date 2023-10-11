# Task
# command to run (to know about variable names)
Here is the sample command to run where you can adjust number of concurrent users and duration of the test. 

jmeter -n -t Task.jmx -l path_to_output -e -o path_for_html_report -Jusers=10 -Jduration=600 (in seconds)
