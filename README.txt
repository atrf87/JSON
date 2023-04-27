// 4. Создать внешний репозиторий c названием JSON.

// 5. Клонировать репозиторий JSON на локальный компьютер 

git clone https://github.com/atrf87/JSON.git

// 6. Внутри локального JSON создать файл “new.json”

cd json

cat > new.json

// 7. Добавить файл под гит

git add new.json

// 8. Закоммитить файл.

git commit -m "new"

// 9. Отправить файл на внешний GitHub репозиторий.

git push

// 10. Отредактировать содержание файла “new.json” - написать информацию о себе. Всё написать в формате JSON.

vi new.json
жмём “I”
{
"name": "Trofimov Andrei Vladimirovich",
"age": 35, 
"animal": "no",
"money": "100 000 rub"
}
Жмём “Esc”
:wq
// 11. Отправить изменения на внешний репозиторий.
git add new.json
git commit -m "my data"
git push
// 12. Создать файл preferences.json
cat > preferences.json
// 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
vi preferences.json
// 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat > sklls.json
{
"skill1": "Testing theory",
"skill2": "API testing",
"skill3": "Manualtestinf",
"skill4": "Stress testing",
"skill5": "SQL"
}
// 15. Отправить сразу 2 файла на внешний репозиторий.
git add .
git commit -m "preferences_skills"
git push
// 16. На веб интерфейсе создать файл bug_report.json.
// 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
// 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
{
  "id": 27,
  "severity": "minor",
  "priority": "high",
  "title": "wrong phone number on home page",
  "environment": "Samsung galaxy A12 Android 12",
  "precondition": "no",
  "steps": "open website www.site.com",
  "expected result": "the correct phone number on the main page is +995 123 456",
  "actual result": "the correct phone number on the main page is +995 000 000",
  "link": "www.site.com",
  "comments": "no"
  "data": "27.04.2023"
}
// 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
// 20. Синхронизировать внешний и локальный репозиторий JSON
git pull

// 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
// 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
// 18. Синхронизировать внешний и локальный репозиторий TXT
git pull
