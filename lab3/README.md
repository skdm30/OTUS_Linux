# Лабораторная работа "Первые шаги с Ansible".

В данной работе используется два виртуальных хоста под управлением ОС Ubuntu 22.04.2:
- ubuntu-otus-01 - хост с которого выполнялось удаленное управление;
- ubuntu-otus-02 - управляемый хост.


Выполнены следующие действия:
- cоздан файл инвенторизации [my_hosts.ini](config/my_hosts.ini);
- отредактирована конфигурационный файл [ansible.cfg](config/ansible.cfg);
- создан файл шаблона конфигурации nginx [nginx.conf.j2](config/templates/nginx.conf.j2);
- создан playbook [install_nginx.yml](config/install_nginx.yml).

После выполнения playbook с хоста управления произведена проверка правильности выполнения работы:
![](pic/man_new.png)  
