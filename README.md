# Documentation

Some observations asome observations about the work developed:

- The profile and event socket module configurations can be overwritten with variables to allow configuration based on your network needs.
- The default values for the variables were provisioned based on the prerequisites of the selection process.
- As far as possible, I used the default values from the freeswitch vanilla settings (including ACLs and passwords). I recommend changing them.
- You may need to modify the ansible settings on your computer.
- To test the cookbook use the command `ansible-playbook site.yml`.