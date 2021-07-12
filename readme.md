# ДЗ по теме "Ansible"

Проект подготовлен в следующей структуре:

> playbooks  
         >> nginx.yml  
staging  
         -- hosts  
templates  
         -- nginx.conf.j2  
Vagrantfile  
ansible.cfg    
readme.md  
***
* playbooks - папка с плейбуком ngin.yml  
* staging - папка с инвентори hosts  
* templates - папка с шаблоном nginx.conf.j2  
* Vagrantfile - файл для поднятия стенда  
* ansible.cfg - файл настроек ansible  
* readme.md - этот файл  
***
После запуска стенда nginx доступен на порту 8080.

