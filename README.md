# test_task

Заменяем пути path , на пути шаблона конфига и путь к файлу index.html
Добавляем на сервер хостинга свой ssh-key после чего запускаем 
Запустите Ansible playbook:
~~~sh
bash ansible-playbook -i hosts nginx-playbook.yml
~~~
Проверка установки
переходим по айпи адресу сервера и проверяем доступность сайта
