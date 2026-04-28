##создаём папку и переходим в неё:
```bash
mkdir example && cd example
```
---
##инициируем git:
```bash
git init
```
---
##связываем с удалённым репозиторием:
```bash
git remote add origin #ссылка ssh
```
---
##создаём или изменяем файлы:
```bash
touch file
```
---
##сохраняем в git:
```bash
git add file
```
---
##делаем коммит:
```bash
git commit -m 'описание'
```
###или 
```bash
git commit
```
###и в открывшемся интерфейсе vi нажимаем i, затем пишем описание, Esc ```qw```
###или q! чтобы закрыть без изменений
---
##загружаем на удалённый репозиторий:
```bash
git push -u origin master(main)
```
---
#готово
---
##дальше после изменений:
###добавляем изменения в git:
```bash
git add files
```
###делаем коммит
```bash
git commit -m 'описание'
```
###добавляем изменения на GitHUb
```bash
git add files
```
---