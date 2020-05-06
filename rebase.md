# Что такое rebase
Применение последовательности коммитов на новый родительский коммит:
![before](https://habrastorage.org/r/w1560/storage2/d15/f9c/605/d15f9c605c1701890cdd8a9b3a1f9d80.png)
![after](https://habrastorage.org/r/w1560/storage2/025/9c0/a2a/0259c0a2acf089365cc677c6c2824473.png)
 - https://m.habr.com/en/post/161009/
 - https://www.atlassian.com/ru/git/tutorials/rewriting-history/git-rebase

# Меняет историю
## Меньше мердж коммитов
До слияния  
![before](http://i.imgur.com/8Wyixm5.png)  
После слияния  
![after merge](http://i.imgur.com/dz09mAc.png)  
После слияния с rebase  
![after rebase merge](http://i.imgur.com/32eE7g2.png)  

## Интерактивный rebase
Переупорядочивание, изменение сообщений, squash  
~/git/git_examples/rebase-i


# Граф коммитов легче читать
Без rebase  
![merges](/branch.png)  
С rebase  
![rebases](/rebase.png)  


# Жирные минусы
## Неожиданный auto merge
https://habr.com/en/post/179123/ 

## Неконсистентные коммиты после rebase
Со слиянием  
![merge](/inconsist_merge.png)  
С rebase  
![merge](/inconsist_rebase.png)  

## Неупорядоченность по времени
