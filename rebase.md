#Что такое rebase
Применение последовательности коммитов на новый родительский коммит:
![before](https://habrastorage.org/r/w1560/storage2/d15/f9c/605/d15f9c605c1701890cdd8a9b3a1f9d80.png)
![after](https://habrastorage.org/r/w1560/storage2/025/9c0/a2a/0259c0a2acf089365cc677c6c2824473.png)
    https://m.habr.com/en/post/161009/
    https://www.atlassian.com/ru/git/tutorials/rewriting-history/git-rebase

#Меняет историю
Меньше мердж коммитов:
До слияние
![before](http://i.imgur.com/8Wyixm5.png)
После слияния
![after merge](http://i.imgur.com/dz09mAc.png)
После слияния с rebase
![after rebase merge](http://i.imgur.com/32eE7g2.png)

Граф коммитов легче читать
![merges](/branch.png)
![rebases](/rebase.png)
