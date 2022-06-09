### 1. Создать внешний репозиторий c названием JSON.</br>
 GitHub->Repositories->New->JSON</br>
### 2. Клонировать репозиторий JSON на локальный компьютер.</br>
git clone <путь к репозиторию></br>
### 3. Внутри локального JSON создать файл “new.json”.</br>
touch new.json</br>
### 4. Добавить файл под гит.</br>
git add new.json</br>
### 5. Закоммитить файл.</br>
git commit -m "новый коммит"</br>
### 6. Отправить файл на внешний GitHub репозиторий.</br>
git push</br>
### 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в   формате JSON.</br>
cat >> new.json  по завершении ctrl+D</br>
### 8. Отправить изменения на внешний репозиторий.</br>
git add new.json</br>
git commit -m "новые данные"</br> 
git push</br>
### 9. Создать файл preferences.json</br>
touch preferences.json</br>
### 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.</br>
cat >> preferences.json</br>
### 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON</br>
touch sklls.json</br>
### 12. Отправить сразу 2 файла на внешний репозиторий.</br>
git add .</br>
git commit -m "два файла"</br>
git push</br>
### 13. На веб интерфейсе создать файл bug_report.json.</br>
Github->Add file->Create new file->bug_report.json</br>
### 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.</br>
commit new file</br>
### 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.</br>
edit this file->commit changes</br>
### 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.</br>
commit changes</br>
### 17. Синхронизировать внешний и локальный репозиторий JSON</br>
git fetch</br>
git pull
