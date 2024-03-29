# Инструкция по работе с GitHub 
### Добавить версионность

Команда  **git init** -  создает локальный репозиторий   
После этого будет создана папка *.git* в том месте, где находится консоль.                                   
*.git* — это папка, которая хранит всю информацию о гит репозитории. Ее удалять не нужно.

### Добавление новых файлов в репозиторий

Команда **git add** - Добавляет файл в репозиторий.         
Теперь наш файл находится под наблюдением *git.* 

### Сохранение изменений файлов     

Команда **git commit** - сохраняет и фиксирует изменения.   
Теперь все сохранения и изменения будут зафиксированы и доступны.

### Статус репозитория 

Команда **git status** - отображает состояние рабочего репозитория  и раздела проиндексированных файлов. С ее помощью можно проверить индексацию изменений и увидеть файлы, которые не отслеживаются *git.*

### Журнал изменений

Команда **git log** - отображает отправленные снимки состояния и позволяет просматривать и фильтровать историю проекта, а также искать в ней конкретные изменения. С помощью *git status* можно просматривать рабочий каталог и раздел проиндексированных файлов, в то время как **git log** показывает только историю коммитов.

### Просмотр и перемещение между изменениями версий

Команда **git checkout** позволяет перемещаться между ветками и коммитами . При переключении ветки происходит обновление файлов в рабочем каталоге в соответствии с версией, хранящейся в этой ветке, а Git начинает записывать все новые коммиты в этой ветке.

* Команда *git checkout master* -  перемещает в гланую ветку 
* Команда *git checkout* (commit hesh) -  перемещает на конкретый коммит 

* Команда *git checkout* -b создает новую ветку.

* Команда *checkout* (_Название ветки_) перемешает нас в другую ветку 
Команда **git diff** -  покажет разницу между ветками и коммитами
Например, _git diff_  (__hesh commit1__).. (__hesh commit2__) выведет разницу в  этих коммитах.
Команда **git branch** - выводит ветки или создает их
branch -  ветка  и не только
еще переулючается между ними        
Для создания новой ветни нужно ввести команду **git branch** (_имя ветки_)  
 Для просмотра списка веток и рабочей ветки необходимо просто ввести команду __git branch__
### Работа с удаленным репозиторием
 Для связывании папки с удаленным репозиторем  необходимо  ввести команду 
 **git remote add origin** (_ссылка на репозиторий  в который дабаляем папку_) 
 **git branch** -M main   теперь основная ветка будет называться **_main_**

Команда **git push** -u origin main отправляет изменения в удаленный репозиторий.  В Первый раз используется  с этими  ключем.      
 Команда **git pull** - скачивает изменения с удаленного репозитория.
