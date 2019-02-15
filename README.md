Install Ansible on AWS.

1. Create a file named set_env.sh with the following content
```
MY_KEY_ID=<AWS key id>
MY_SECRET_ACCESS_KEY=<AWS secret access key>
MY_REGION=<region for provisioned environment>
ANSIBLE_PASSWROD=<password for initial users>
```
2. Run the command
```
./run.sh
```
This will provision an Ansible Tower machine on AWS.

After starting up the server, you need a license file. For trying out Ansible, you can get a license key at the following location https://www.ansible.com/workshop-license.
