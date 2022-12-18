# Шпаргалка по работе с git
### Инициализация пользователя и электронной почты
* git config --global user.name "first and second name or nickname"
* git config --global user.email "email@domen.com"

### Инициализация нового или уже существующего репозиторя
* git init

### Добавление всех или отдельных файлов в область подготовленных файлов
* git add .
* git add name.txt

### Проверка статуса репозитория
* git status

### Создание коммита с однострочным сообщением либо сообщение через редактор
* git commit -m "Your message"
* git commit

### Просмотр логов, просмотр логов с изменениеями и односмтрочный просмотр логов
* git log
* git log -p
* git log --oneline

### Изменение последнего коммита
* git commit --amend -m "message"

### Просмотр заданного коммита
* git show 1f915694954a74248d8226cbe34d0e81b8b08aa7
либо
* git show 1f9156

### Просмотр списка изменений
* git diff

### Отмена подготовленных и неподготовленных изменений
* git checkout namefile.txt

### Просмотр всех веток
* git branch

### Переключение на другую ветку
* git swith name_branch

### Слияние двух веток
* git merge name_branch

### Отображение журнала коммитов для всех веток
* git log --graph
* git log --graph --oneline --decorate

По всем веткам:
* git log --all --graph --oneline --decorate



# Работаем с github

### Алгоритм стягивания репозитория с github
* git remote add origin https://github.com/userName/link.git
* git branch -M main
* git push -u origin main

### Отправка на github измененый репозитория
* git push

### Стягивание c github (стягиваем с сайта репозиторий)
* git pull

## Pull request
1) Делаем fork репозитория;
2) После клонируем репозиторий себе на компьютер либо не клонируем;
3) Вносим изменения в репозиторий;
4) Добавляем файл, делаем коммит;
5) Пушим на github либо не пушим, если вносили изменения на github;
6) Производим pull request из под своего репозитория в репозиторий автора.