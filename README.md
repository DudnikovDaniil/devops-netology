# devops-netology

Репозиторий для домашних заданий по курсу DevOps

## Описание
Этот репозиторий создан для выполнения домашних заданий в рамках курса по DevOps.

## .gitignore
Файл .gitignore настроен для проектов Terraform. Будут игнорироваться:
- Локальные каталоги `.terraform/`
- Файлы состояний `.tfstate` и `.tfstate.backup`
- Файлы переопределений `override.tf` и `override.tf.json`
- Файлы с переменными `terraform.tfvars` и `*.auto.tfvars`
- Логи `crash.log`
- Файлы, содержащие чувствительные данные (пароли, ключи)

## Выполненные действия
1. Создан репозиторий на GitHub
2. Настроен локальный Git
3. Созданы коммиты:
   - First commit (обновление README.md)
   - Added gitignore (добавлен .gitignore)
   - Prepare to delete and move (добавлены временные файлы)
   - Moved and deleted (удален will_be_deleted.txt, перемещен will_be_moved.txt в has_been_moved.txt)
4. Изменения отправлены в удаленный репозиторий
