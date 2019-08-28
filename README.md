##安裝
- brew install ansible
- brew install https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb

##使用
- move hosts->/etc/ansible/hosts

- ad-hoc command
ansible bet -m setup
- playbook
ansible-playbook playbook/setup.yml
