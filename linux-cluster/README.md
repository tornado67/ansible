При запуске плейбука через параметр --extra-vars необхожимо передать список хостов на которых он будет запущен:

ansible-playbook setup.yml --extra-vars="target=\<hosts\>"
