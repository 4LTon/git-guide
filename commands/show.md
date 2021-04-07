[< к содержанию](../readme.md)

## git show

---
Синтаксис :
```bash-
git show <хеш коммита>
```

Данная команды выводит информацию определенного коммита по его ХЕШу.

Пример :
```bash-
PS C:\Users\User\OneDrive\Рабочий стол\task_4> git show 418640511e410193a2da5cc63e67c342c17a5d2e
```
```bash-
commit 418640511e410193a2da5cc63e67c342c17a5d2e
Author: 4LTon <glotov.vd@yandex.ru>
Date:   Wed Apr 7 14:32:05 2021 +0300

    added clone.md

diff --git a/commands/clone.md b/commands/clone.md
new file mode 100644
index 0000000..4039c9a
--- /dev/null
+++ b/commands/clone.md
@@ -0,0 +1,15 @@
+[< к содержанию](../readme.md)
+
+## git clone
+---
+Синтаксис :
+```bush-
+git clone <path>
+```
+
+Ланная команда служит для копирования содержимого удаленного репозитория на локальный.
+
+Пример : 
+```bash-
+git clone https://github.com/example
+```
\ No newline at end of file
diff --git a/commands/init.md b/commands/init.md
index a30c14f..6408d57 100644
--- a/commands/init.md
+++ b/commands/init.md
@@ -7,4 +7,4 @@
 git init
 ``
-Создание репозитория
\ No newline at end of file
+Создание локального репозитория.
\ No newline at end of file
diff --git a/readme.md b/readme.md
index 005c297..eadb26a 100644
--- a/readme.md
+++ b/readme.md
@@ -14,4 +14,5 @@ LICENSE: [MIT](./license.md)
     * [git status](./commands/status.md)
     * [git commit](./commands/commit.md)
     * [git push](./commands/push.md)
+    * [git clone](./commands/clone.md)
 ---
\ No newline at end of file
(END)
```
