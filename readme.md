# ДЗ по теме "Ansible"

Проект подготовлен в следующей структуре:

playbooks  
          \
            nginx.yml
staging--
        |
        hosts
templates--
          |
          nginx.conf.j2
Vagrantfile
ansible.cfg

playbooks - папка с плейбуком ngin.yml
staging - папка с инвентори hosts
templates - папка с шаблоном nginx.conf.j2
Vagrantfile - файл для поднятия стенда
ansible.cfg - файл настроек ansible

После запуска стенда nginx доступен на порту 8080.

