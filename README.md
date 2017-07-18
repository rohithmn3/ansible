# Ansible
Deploying a webserver

Note: 
1) /var/www/html is mounted on the device /dev/sdb (volume)
2) Consider using get_url module rather than wget.

HANDLERs: Handlers are just like regular tasks in an Ansible playbook, but are only run if the Task contains a notify directive and also indicates that it changed something. For example, if a config file is changed, then the task referencing the config file templating operation may notify a service restart handler.
