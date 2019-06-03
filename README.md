#Стартовый шаблон HTML 5
## Клонирование шаблона
1. Открываем папку с проектами, и удерживая Shift правой клавишей мыши вызываем меню, выбираем Открыть окно комманд (в Windows 7) или PowerShell (в Windows 10)
2. Клонируем репозиторий: git clone https://github.com/Alexpotkin/GulpTemplate.git NameNewProject
3. Переходим в созданную папку с проектом: cd NameNewProject

Примечание: При клонировании на выходе вы получаете вполне отдельный и самостоятельный репозиторий с ссылкой на оригинальный. Если вам она так не нравится можете удалить, но обычно смысла в этом маловато.

4. Далее создаем пустой репозиторий на Github
5. Добавляем репозиторий git remote add NameNewProject https://github.com/Alexpotkin/NameFirstProject.git
6. git push -u FirstProject master