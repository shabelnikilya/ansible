ping:
	ansible all -i inventory.ini -u root -m ping

alias:
	ansible all --limit new_server -i inventory.ini -u root -m ping

run_playbook:
	ansible-playbook redis-playbook.yaml -i inventory.ini

install_git:
	ansible-playbook git-install.yaml -i inventory.ini

remove_git:
	ansible-playbook git-remove.yaml -i inventory.ini

nginx:
	ansible-playbook nginx.yaml -i inventory.ini

main:
	ansible-playbook main.yaml -i inventory.ini

role:
	ansible-playbook roles.yaml -i inventory.ini