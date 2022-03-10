## VCS_task_4

Задача: откатить `merge` в `main`.

### Ход работы

Исходная ситуация:
![](img/git_1.png)

Команды:
```
$ git checkout main
$ git reset HEAD^
$ git push -f
```

![](img/git_2.png)
