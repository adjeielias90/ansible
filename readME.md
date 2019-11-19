
ansible-playbook apache.yml -K

'''
  '-K' flag tells ansible to prompt for a password in case of actions that require sudo

'''
  To set up a passwordless sudo: https://code-maven.com/enable-ansible-passwordless-sudo