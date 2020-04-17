## Решение  
после команды 'git clone' перейти в  каталог './10.Ansible/homework' запустить scritpt.sh, сценарий запустит 'vagrant up' и вытянет соответствующие порты для localhost каждой виртуалки в файлы 'inventory'. Плюс скрипт соберет информацию для файла ~/.ssh/know_hosts, чтобы при запуске playbook локальная машина уже знала целевые хосты.
Далее из каталога './10.Ansible/homework' запускаем playbook  

```
ansible-playbook -i inventory/ nginx.yml
```


Дополнительная информация:  
pip  
zsh  
id_rsa  
[bashrc](https://pingvinus.ru/note/bash-promt)  
