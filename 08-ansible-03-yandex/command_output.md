# Домашнее задание к занятию 3 «Использование Ansible»

## Основная часть

1. Допишите playbook: нужно сделать ещё один play, который устанавливает и настраивает LightHouse.

![image](https://github.com/SemenAmbarnov/ansible-homework/assets/92155007/34d5944f-b8eb-435c-854f-392a1802f3f7)

![image](https://github.com/SemenAmbarnov/ansible-homework/assets/92155007/f2efc880-d2ee-4394-a22f-3adaefb8fa5d)

2. При создании tasks рекомендую использовать модули: `get_url`, `template`, `yum`, `apt`.
3. Tasks должны: скачать статику LightHouse, установить Nginx или любой другой веб-сервер, настроить его конфиг для открытия LightHouse, запустить веб-сервер.
4. Подготовьте свой inventory-файл `prod.yml`.

![image](https://github.com/SemenAmbarnov/ansible-homework/assets/92155007/e676dde8-c704-45ac-b405-49575bd77e31)

5. Запустите `ansible-lint site.yml` и исправьте ошибки, если они есть.

![image](https://github.com/SemenAmbarnov/ansible-homework/assets/92155007/31565cfa-0d2f-48e2-8bab-75eb3be2ef8a)

6. Попробуйте запустить playbook на этом окружении с флагом `--check`.
7. Запустите playbook на `prod.yml` окружении с флагом `--diff`. Убедитесь, что изменения на системе произведены.
8. Повторно запустите playbook с флагом `--diff` и убедитесь, что playbook идемпотентен.


![image](https://github.com/SemenAmbarnov/ansible-homework/assets/92155007/1b9dc9b0-eb50-4b3b-962c-8ce391989e2f)

![image](https://github.com/SemenAmbarnov/ansible-homework/assets/92155007/2c6758f7-ed4e-4558-b6f8-f4a49509effd)

![image](https://github.com/SemenAmbarnov/ansible-homework/assets/92155007/4f45fe7f-2f21-4be5-9f1f-2fd6cce26ad4)

9. Подготовьте README.md-файл по своему playbook. В нём должно быть описано: что делает playbook, какие у него есть параметры и теги.
10. Готовый playbook выложите в свой репозиторий, поставьте тег `08-ansible-03-yandex` на фиксирующий коммит, в ответ предоставьте ссылку на него.


