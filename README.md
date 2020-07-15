# ansible-zabbix
#commands
check agent version
zabbix_agentd -V
# group_vars usage
creating directory group_vars
with multiple .yml files inside
e.g server.yml and agent.yml
group_vars/all directory inside with main.yml file to define variables for all inventory groups.
# handlers usage
in task body
notify: "the name of handler/the listne of handler"
new srtucture in task level
handlers:
  -name "the name of handler"
   listen: "the name for grouping multiple handlers"
   


