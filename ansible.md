# Ansible

Чтобы команда, которая отдаёт свой результат через register, выполнилась даже в режиме check (+ помечаем как changed только в случае ошибки):
```
check_mode: no
changed_when: current_apix_port_raw.rc != 0
```
