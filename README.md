# test_task


Добавляем на сервер хостинга свой ssh-key после чего запускаем 
Запустите Ansible playbook:
~~~sh
bash ansible-playbook -i hosts lamp-playbook.yml
~~~
~~~sh
bash ansible-playbook -i hosts ufw-zabbix.yml
~~~
Проверка установки
переходим по айпи адресу сервера и проверяем доступность сайта

