# ***Инструкция по работе с GIT для начинающих***

![](./assets/1280px-Git-logo.svg.png)

GIT logo by Jason Long. http://git-scm.com/downloads/logos

lisense: [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
___
LICENSE: [MIT](./license.md) 
___
## Содержание
+ [git clone](./clone)      
+ [git init](./int)
+ [git add](./add.md) 
+ [git commit](./commit)
+ [git statu](./assets/status.md)
+ [git branch](./branch.md)
+ [git chekout](./chekout.md)
+ [git merge](./merge.md)
+ [git push](./push.md)
+ [git pull](./pull.md)
___

## ***ОСНОВНЫЕ КОИАНДЫ***

**git clone *" ссылка на репозиторий"*** - для переноса с сайта на ПК

**git init**- создать пустой репозиторий

**git add  *[file]***- Эта команда добавляет файл в индекс.

```bash=
git add .- с помощью данной команды в каталог добавляются все файлы кроме игнорируемых.
```

**git commet**- для записи действий с файлами

```bash=
git commit -m"name file"- для записи действий с определенным файлом
```

**git status**- показывает состояния файлов в рабочем каталоге и индексе:
 какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе.