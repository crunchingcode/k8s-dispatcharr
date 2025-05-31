# k8s-dispatcharr
ansible playbook for k8s and dispatcharr.  This runs dispatcharr modularly.  the AIO wasn't working.  The modular way was recommended by Slamanna212@discord.  Run the dispatchar-site.yml  this will run the playbooks in order.  if you want to upgrade you can change the version in said playbook and run the playbook individually.  

You should add a definition in vars file to include the postgres password and any other secret/password definitions in the playbook(s).

This also assumes you want the namespace livetv.  Change it throughout if you want something different.

Doug
