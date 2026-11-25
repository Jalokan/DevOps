# Ansible-проект раскатки микросервисов

    ansible-playbook firstPlaybook.yml --ask-vault-pass                 # полная раскатка
    ansible-playbook firstPlaybook.yml --ask-vault-pass --tags start    # запуск контейнеров
    ansible-playbook firstPlaybook.yml --ask-vault-pass --tags stop     # остановка контейнеров
