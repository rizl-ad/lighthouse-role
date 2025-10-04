Lighthouse
=========

Данная роль устанавливает nginx, необходимый для работы Lighthouse, скачивает Lighthouse из репозитория и создает конфигурационный файл lighthouse для nginx.

Role Variables
--------------

| переменная | описание |
| ---------- | -------- |
| lighthouse_url | путь к репозиторию Lighthouse |

Example Playbook
----------------

    - hosts: servers
      roles:
         - clickhouse

License
-------

MIT

Author Information
------------------

Yaroslav Lysenko
