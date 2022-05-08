# git_homework_2
Git homewok on Vadim Ksendzov course 
Git second homework 
1. На локальном репозитории сделать ветки:
    + git branch Jmeter
    + git branch Postman
    + git branch CheckLists
    + git branch Bug_reports
    + git branch SQL
    + git branch Charles
    + git branch Mobile_testing
2. Запушить все ветки на внешний репозиторий
    + git push -u origin Jmeter Postman CheckLists Bug_reports SQL Charles Mobile_testing
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
    + git checkout Bug_reports
    + touch bug_report_structure.txt
    + vim bug_report_structure.txt
4. Запушить структуру багрепорта на внешний репозиторий
    + git add .
    + git commit -m "Add bug_report_structure.txt"
    + git push 
5. Вмержить ветку Bag Reports в Main
    + git checkout main
    + git merge Bug_reports
6. Запушить main на внешний репозиторий.
    + git push
7. В ветке CheckLists набросать структуру чек листа.
    + git checkout CheckLists
    + touch chek_list_structure.txt
    + vim chek_list_structure.txt
8. Запушить структуру на внешний репозиторий
    + git add chek_list_structure.txt
    + git commit -m "Add chek_list_structure.txt"
    + git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
  на github:
    + нажать compare & pull request
    + нажать Create pull request
    + нажать Merge pull request
    + нажать Confirm merge
10. Синхронизировать Внешнюю и Локальную ветки Main
    + git checkout main
    + git pull
