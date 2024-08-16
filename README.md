Confluent Kafka Installer v1.1
=========

Роли для очистки и установки кластера Confluent Kafka указанной версии.

Предупреждение
------------

Данная роль проверена только на Ubuntu 20.04.6 LTS

Переменные
--------------

Файл inventory-kafka.yml - содержит список хостов на которых необходимо развернуть ноды kafka
Файл play-install-kafka.yml - содержит список запускаемых ролей

Запуск
----------------

Комманда для запуска роли

---
ansible-playbook -i inventory-kafka.yml play-install-kafka.yml -e HOST=all


Автор
------------------

KapelaN74, 2024г