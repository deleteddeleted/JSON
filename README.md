# JSON
4. Создать внешний репозиторий c названием JSON.  
 На вэбе Repositories --> New --> Repository name:JSON --> Check "Add a README file" -->  "Create repository"

 5. Клонировать репозиторий JSON на локальный компьютер.  
git clone https://github.com/deleteddeleted/JSON.git

 6. Внутри локального JSON создать файл “new.json”.  
touch new.json

 7. Добавить файл под гит.  
git add new.json

 8. Закоммитить файл.  
git commit -m "Добавление файла на внешний репозиторий"

 9. Отправить файл на внешний GitHub репозиторий.  
git push

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
vim new.json  
i   
{  
        "name": "Nastya",  
        "surname": "Vinogradova",  
        "age" : 25,  
        "pets" : 1,  
        "salary" : 250000  
}  
esc :wq enter  

 11. Отправить изменения на внешний репозиторий.  
git status  
git add .  
git status  
git commit -m "Содержание файла отредактировано"  
git push  

 12. Создать файл preferences.json  
touch preferences.json  

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
vim preferences.json  
i  
{  
        "favorite movie" : "The Book Thief",  
        "favorite TV series" : "13 Reasons Why",  
        "favorite food" : "pizza",  
        "favorite time_year" : "Summer",  
        "country" : "Norway"  
}  
esc :wq enter  

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  
touch sklls.json  
vim sklls.json  
i  
{  
	"skill_1" : "Terminal",  
	"skill_2" : "GitBash",  
	"skill_3" : "GitHub",  
	"skill_4" : "Postman",  
	"skill_5" : "API",  
	"skill_6" : "Test case"  
}  
esc :wq enter  

 15. Отправить сразу 2 файла на внешний репозиторий.  
git status  
git add .  
git status  
git commit -m "Отправлены 2 файла одновременно"  
git push

 16. На веб интерфейсе создать файл bug_report.json.  
Add file --> Create new file --> Name: bug_report.json

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
Commit New File

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
bug_report.json --> Edit this file  
{  
    "ID" : "1",  
    "Summary" : "Не работает кнопка отправки заказа",  
    "Preconditions": "Зайти на сайт",  
    "Steps to Reproduce":{  
          "Step1":"<Пролистать до поля >",  
          "Step2":"<Ввести значение в поле>",  
          "Step3":"<Попытаться нажать кнопку отправки заказа>"            
        },  
    "Actual result": "кнопка неактивна",  
    "Expected result": "кнопка нажимается, можно сделать заказ"  
    "Attachments":"<link>"  
}  

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
Commit changes  

 20. Синхронизировать внешний и локальный репозиторий JSON  
git pull  
