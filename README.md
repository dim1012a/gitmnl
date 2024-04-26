# Начало работы с GitHub (пособие для чайников)

## Установка Git Bash на локальном компьютере.

### Основные команды с файлами.

- Чтобы создать файл, нужно ввести в консоль команду touch (англ. «коснуться») с именем файла в качестве параметра: touch %ИМЯ_ФАЙЛА%.
- Для создания директорий через терминал используют другую команду — mkdir.
- Чтобы удалить файл, нужно напечатать команду rm (от англ. remove — «удалить») и передать ей имя файла.
- Удалить папку можно командой rmdir.

### Работа с репозиторием.

- Работа с файлом настройки .gitconfig
- Сделать папку репозиторием — git init
- «Разгитить» папку, если что-то пошло не так, — rm -rf .git
- Добавляем файлы в репозиторий $ git add --all # подготовили к сохранению все файлы в репозитории
- Сделать коммит можно командой git commit c ключом -m (от англ. message — «сообщение»), который присваивает коммиту сообщение.
- Генерируем **SSH ключи**. 

'''bash
$ clip < ~/.ssh/id_rsa.pub
# для ed25519:
$ clip < ~/.ssh/id_ed25519.pub
'''

### Платформа GitHub

---
[GitHub](https://github.com)
---
- Регистрируемся. GitHub — платформа для хранения IT-проектов и совместной работы над ними с использованием Git. 
- Создаем репозиторий.
- Связываенм SSH-ключ и GitHub-аккаунт
- Связываем удаленный репозиторий с локальным.
- Оформляем проект, создаем файл README.txt