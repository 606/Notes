Данные правила существуют для создания единой архитектуры данных на базе MySQL, MSSQL-серверов.

----------


**1. БД.**  

Испольузем стиль **PascalCase**, для двухсимвольных аббревиатур можно использовать **UPPERCASE**.

Пример:

    PascalCase: ThisIsTestDB
    UPPERCASE: CB

**2. Схемы.**  

Испольузем стиль **lowercase**, исключением может быть **PascalCase.**
Имя схемы должно содержать логический смысл.

Пример:

    testschema
    TestSchema


**3. Таблицы.**  

Испольузем стиль **PascalCase**, исключением может быть **lowercase** с исползованием нижнего подчеркивания.

Имя таблицы должно содержать логический смысл,

Пример:

    dbo.TestTable
    dbo.test_table



**4. Колонки в таблицах, представлениях.** 
 
Используем стиль **camelCase**, для двухсимвольных абрревиатур используем **UPPERCASE**. 

Имена колонок должны содержать логический смысл.

Пример:


    columnID, columnDate, DD, statusID, statusType, remark
   
    

**5. Объявление переменных, аргументов.**  

Используем стиль **camelCase,** для двухсимвольных абрревиатур используем **UPPERCASE**. 

Имена переменных/аргументов должны содержать логический смысл.

Пример:

    declare @argumentID int 
    declare @datestart datetime
    declare @typeID int 
    declare @debug bit 


**6.Процедуры.**  

Используем префикс **proc_**. Для имен использузем стиль **PascalCase.**

Имя процедуры должно содержать логический смысл.

Пример:

    proc_ThisIsTestProc
    proc_TestCreateDB


**7. Триггеры.**  

Используем префикс **TR_**. Для имен использузем стиль **PascalCase**.

Имя тригерра должно содержать логический смысл.

Пример:

    TR_TriggerName

**8. Индексы.**  

Используем префикс **IX_**. Для имен использузем стиль **PascalCase**.

Имя индекса должно содержать название колонок, по которым выполняется фильтр.

Пример:

    IX_colID
    IX_coName


**9. Первичные ключи.**  

Используем префикс **PK_**. Для имен использузем стиль **PascalCase**.
Имя первичного ключа должно содержать название колонок, которым(-ому) присвается превичный ключ.

Пример:

    PK_colID
    PK_coName


**10. Внешние ключи.**  

Используем префикс **FK_**. Для имен использузем стиль **PascalCase**.

Имя внешнего ключа должно содержать название колонок, которым(-ому) присвается внешний ключ.

Пример:

    FK_colID
    FK_coName

**11. Значения "по-умолчанию" (default).**  
Используем префикс **DF_**. Для имен использузем стиль PascalCase
Имя значения должно содержать название колонок, которым(-ому) присвается значение по-умолчанию.

Пример:



    DF_colID
    DF_coName

**12. Проверки.**  

Используем префикс **CK_**. Для имен использузем стиль **PascalCase**.
Имя проверки должно содержать название колонок, которым(-ому) выполняется проверка.

Пример:

    CK_colID
    CK_coName


**13. Представления** 
 
Используем префикс **view_**. Для имен использузем стиль **PascalCase**, исключением может быть lowercase с исползованием нижнего подчеркивания.

Имя представления должно содержать логический смысл.

Пример:

    view_ViewName
    view_view_namestrong text
