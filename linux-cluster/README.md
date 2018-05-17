При запуске плейбуку черех параметра --extra-vars необхожимо передать списко хосто на которых он будет запущен:

ansible-playbook setup.yml --extra-vars="target=\<hosts\>"