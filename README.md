# HW_Git_JSON

 4. Создать внешний репозиторий c названием JSON.
 5. Клонировать репозиторий JSON на локальный компьютер.
 
     > git clone https://github.com/dkovalenkoqa/HW_Git_JSON.git
 6. Внутри локального JSON создать файл “new.json”.
     > touch new.json
 7. Добавить файл под гит.
     > git add new.json
 8. Закоммитить файл.
     > git commit -m "added new.jsom
 9. Отправить файл на внешний GitHub репозиторий.
     > git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
     > nano new.json
     ```
      {
         "Name" : "Dima",
         "LastName" : "Kovalenko",
         "MiddleName" : "Mikhailovich",
         "Age" : 22,
         "Pets" : 0,
         "Salary" : "500$"
      }
     ```
 11. Отправить изменения на внешний репозиторий.
     > git add new.json

     > git commit -m "update new.json"

     > git push
 12. Создать файл preferences.json
     > touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
     > nano preferences.json
     ```
      {
         "Favorite film" : "lots of",
         "Favorite Series" : "lots of",
         "Favorite Food" : "lots of",
         "Favorite Season" : "Summer",
         "Coutry which i want to visit" : "Switzerland"
      }
     ```
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
     > nano skills.json
     ```
      {
         "1" : "Terminal",
         "2" : "Git",
         "3" : "Postman",
         "4" : "Python",
         "5" : "Fiddler",
         "6" : "Jmeter",
         "7" : "SQL"
      }
     ```
 15. Отправить сразу 2 файла на внешний репозиторий.
     > git add preferences.json skills.json

     > git commit -m "add preferences.json skills.json
 16. На веб интерфейсе создать файл bug_report.json.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
     ```
      {
         "Bug_Name" : "Application crashes upon clicking the SAVE button while creating a new user.",
         "Bug ID" : "(It will be automatically created by the BUG Tracking tool once you save this bug).",
         "Area Path" : "USERS menu -> New Users",
         "Build Number" : "Version Number 5.0.1",
         "Severity" : "HIGH (High/Medium/Low) or 1",
         "Priority" : "HIGH (High/Medium/Low) or 1",
         "Assigned to" : "Developer-X",
         "Reported By" : "Your Name",
         "Reported On" : "Date",
         "Reason" : "Defect",
         "Status" : "New/Open/Active (Depends on the Tool you are using)",
         "Environment" : "Windows 2003/SQL Server 2005"
      }
     ```
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 20. Синхронизировать внешний и локальный репозиторий JSON.

      > git pull
