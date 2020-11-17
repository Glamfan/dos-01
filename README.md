# dos-01
Test
Создание ветки1
git checkout -b Task7-1

Эмуляция фичи1
nano ficha1.txt

Коммит1
git add ficha1.txt
git commit -m "Ficha1"

Те же действия для второй и третей ветки

ilia@ilia-B450:~/dos-01$ git branch
* Task7-1
  Task7-2
  Task7-3
  dev
  main

git merge Task7-2
git merge Task7-3

удаляем лишние ветки

git brunch -d Task7-3
