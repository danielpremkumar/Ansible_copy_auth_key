ansible-playbook -i <inventory-file> playbook.yml --ask-pass --extra-vars='pubkey="<pub-key>"' -e "ansible_user=daniel"

------------------------------------------------------------------------------------------------------------------------------------
ansible-playbook playbook.yml --ask-pass --extra-vars='pubkey="<pub-key>"' -e "ansible_user=daniel"


ansible-playbook playbook.yml --ask-pass --extra-vars='pubkey="<pub-key>"' -e "ansible_user=daniel"
-----------------------------------------------------------------------------------
ansible-playbook resetPassword.yml --ask-pass -e "ansible_user=daniel"


-------------------------------------------------------------------------------------------
ansible-vault create --vault-id newPass@prompt vault1.yml
