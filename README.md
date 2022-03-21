# Ansible Role s-nail

install s-nail with docker

## Collection dependencies

The role depends on the collection community.docker.
Note that this also requires installation of the python library `docker`.

## Role Variables

<!-- markdownlint-disable MD033 -->
| group | variable | default | description |
| --- | --- | ---| --- |
| mail | s_nail_smtp_server | | used for SMTP_SERVER |
| mail | s_nail_smtp_port | | used for SMTP_PORT |
| mail | s_nail_mail_from | | used for MAIL_FROM |
| mail | s_nail_mail_user | | used for MAIL_USER |
| mail | s_nail_mail_password | | used for MAIL_PASSWORD |
<!-- markdownlint-enable MD033 -->
