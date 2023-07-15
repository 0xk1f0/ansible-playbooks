# What does this do

Some of the stuff I always do on my ubuntu containers these days

- Set a new SSH Port and deploy my SSH key
- Remove the new SSH socket integration introduced in Ubuntu 22.10 so you can actually change Ports
- Allow the new SSH Port in UFW and enable it

# How to run

Change the example files in this dir and run

```bash
ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -i inventory.ini playbook.yaml
```
