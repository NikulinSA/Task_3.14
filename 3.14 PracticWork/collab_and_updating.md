[К СОДЕРЖАНИЮ](/readme.md)

*[< НАЗАД](branch_merge.md)*

---

# Совместная работа и обновление проектов

## **git fetch**
Команда **git fetch** связывается с удалённым репозиторием и забирает из него все изменения, которых у вас пока нет и сохраняет их локально.
```
git fetch [remote-name]
```

## **git pull**
Команда **git pull** работает как комбинация команд *git fetch* и *git merge*, т. е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.

## **git push**
Команда **git push** используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий. 

Этой команде нужно право на запись в репозиторий, поэтому она использует аутентификацию.

## **git remote**
Команда **git remote** служит для управления списком удалённых репозиториев. Она позволяет сохранять длинные URL репозиториев в виде понятных коротких строк, например «origin», так что вам не придётся забивать голову всякой ерундой и набирать её каждый раз для связи с сервером. Вы можете использовать несколько удалённых репозиториев для работы и git remote поможет добавлять, изменять и удалять их.
```
git remote add <имя> <URL>
```

## **git archive**
Команда **git archive** используется для упаковки в архив указанных коммитов или всего репозитория.

## **git submodule**
Команда **git submodule** используется для управления вложенными репозиториями. Например, это могут быть библиотеки или другие, используемые не только в этом проекте ресурсы. У команды submodule есть несколько под-команд — add, update, sync и др. — для управления такими репозиториями.

---
[ДАЛЕЕ >](Inspection.md)
