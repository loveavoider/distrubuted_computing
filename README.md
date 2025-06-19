# Distributed Computing ITMO

## Студент: Павлюченков Евгений
### [Ссылка на разворачиваемый проект](https://github.com/loveavoider/kittygram)

## Инструкция по запуску
#### 1. Скопировать _env.example в .env
```bash
cp ansible/files/_env.example ansible/files/.env
```
#### 2. Поменять хосты в файле
```
ansible/hosts
```
#### 3. Порядок запуска плейбуков
```
ansible/install_docker_playbook.yml
ansible/run_application_playbook.yml
ansible/configure_replica_playbook.yml
```
