# Памятка по работе с удаленными репозиториями.

Для создания удаленного репозитория необходимо иметь учетную запись на ресурсе, предоставляющем подобные возможности. Мы воспользуемся **[GitHub](https://github.com/)**.

1. Скопировать (fork) нужный репозиторий в свой аккаунт Github.
2. **git clone <url_of_remote_repo>**.
3. **git checkout -b <branch_to_offer>**.
4. Редактировать в желаемом объеме.
5. **git push**.
6. Инициировать pull request на Github.

**NB!** Если возникают проблемы - внимательно читать строку терминала и вообще внимательно читать!

не забыть добавить инструкцию по добавлению на GitHub существующего локально репозитория. …or push an existing repository from the command line
git remote add origin https://github.com/KSolo0203/Push_pull.git
git remote set-url origin https://github.com/KSolo0203/Push_pull.git
git branch -M main
git push -u origin main

Пулл реквест по адресу https://github.com/GiliazovaPullrequests/VersionControl_Seminar3