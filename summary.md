1. git clone <repo-link> - clone the repo
2. `git status` - always
3. git pull - оновити локальну гілку відповідно до віддаленої гілки на гітхабі
4. git checkout -b branch_name - створити нову гілку і переключитися на неї
5. git add - додати зміни (чи нові файли) в індекс перед комітом
6. git commit -m 'commit message' - створити коміт з повідомленням
7. git push origin branch_name - запушити зміни (при першому пуші створюється пул реквест)

- git restore filename - прибрати непроіндексовані зміни
- git resore --staged filename - прибрати проіндексовані зміни (щоб файл не потрапив в коміт)
- git reset HEAD~1 - відмінити один попередній коміт
- `git stash` / `git stash apply` - тимчасово сховати / повернути сховані файли
