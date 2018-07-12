# TSC-task-3
![Image alt](http://publishernews.ru/images/PressReleases/press_r_34E7C198-ED6D-4243-B3E4-12882A5A701A.jpg)

>Требуется написать программу, которая ищет все вхождения указанной подстроки в текстовых файлах и выводит найденные строки, содержащие подстроку, в выходной файл. 
>Поиск должен быть регистронезависимым и осуществляться в многопоточном режиме.
>Входные параметры:
>1. Количество потоков, которые может использовать программа
>2. Искомая подстрока
>3. Начальный каталог (поиск должен производиться во всем дереве дочерних каталогов)
>4. Выходной файл с результатами
>5. Список расширений файлов, в которых должен осуществляться поиск.
>
>В выходной файл информация должна выводиться в следующем формате:
>[Номер потока] Относительный путь (от начального каталога) - Имя файла : найденная строка
>В конце файла должна содержаться информация об общем времени поиска в секундах.
>
>Пример входных параметров:
>10 Error c:\logs c:\temp\out.txt txt log out

_____________________________________________________________________________________________________
### Формат ввода:
resources

### Формат вывода:
**result.txt**
>_____________________________________________________________________________________________________