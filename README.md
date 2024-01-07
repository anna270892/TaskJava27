# План автоматизации: тестирование возможности записаться на обучение профессии «Тестировщик ПО»

## Перечень автоматизируемых сценариев.

**Тестирование перехода к форме записи:**
1. поиск формы записи с главной страницы
* открыть сайт в браузере https://netology.ru/
* проскроллить главную страницу вниз до блока с названием "Если у вас остались вопросы — мы поможем" и формой записи
* в поле "Имя" ввести имя: Анна
* в поле "Телефон" ввести телефон: +79500060445
* нажать кнопку "Получить консультацию"  
Ожидаемый результат: появилось модальное окно с текстом: "В ближайшее время с вами свяжется менеджер"
2. открытие формы записи через блок "Направление обучения" на главной странице через кнопку "Полный каталог" - "Тестировщик ПО"
* открыть сайт в браузере https://netology.ru/
* проскроллить главную страницу вниз до блока с названием "Направления обучения"
* нажать на кнопку "Полный каталог"
* просколлить страницу вниз до профессии "Тестировщик ПО"
* нажать на ссылку "Тестировщик ПО"
3. открытие формы записи через "Каталог курсов" на главной странице - "Программирование" - "Тестировщик ПО"
* открыть сайт в браузере https://netology.ru/
* в верхнем меню нажать на кнопку "Каталог курсов"
* из предложенного списка выбрать "Программирование"
* просколлить страницу вниз до профессии "Тестировщик ПО"
* нажать на ссылку "Тестировщик ПО"

**Тестирование формы записи:**
1. валидная отправка формы с кнопкой "Записаться"
* открыть сайт в браузере https://netology.ru/
* проскроллить главную страницу вниз до блока с названием "Если у вас остались вопросы — мы поможем" и формой записи
* в поле "Имя" ввести имя: Анна
* в поле "Телефон" ввести телефон: +79500060445
* нажать кнопку "Получить консультацию" 
1. пустая отправка формы с кнопкой "Записаться"
1. отправка формы только с пустым полем ФИО с кнопкой "Записаться"
1. отправка формы только с пустым полем телефон с кнопкой "Записаться"
1. отправка формы только с пустым полем email с кнопкой "Записаться"
1. отправка формы только с пустым полем ФИО с кнопкой "Записаться"
1. валидная отправка формы с кнопкой "Получить консультацию"
1. пустая отправка формы с кнопкой "Получить консультацию"
1. отправка формы только с пустым полем ФИО с кнопкой "Получить консультацию"
1. отправка формы только с пустым полем телефон с кнопкой "Получить консультацию"
1. отправка формы только с пустым полем email с кнопкой "Получить консультацию"
1. отправка формы только с пустым полем ФИО с кнопкой "Получить консультацию"


## Перечень используемых инструментов с обоснованием выбора.
1. IntelliJ IDEA - для написания автотестов на Java, преимущества: функциональность, большой выбор интсрументов для работы с кодом, эргономичность, комфортность.
1. Язык программирования Java - для написания автотестов, премущества: простота, безопасность, производительность, независимость от аппартаной части и операционной системы.
1. Docker - для запуска базы данных, премущества: портативность, изоляция, последовательность, масштабируемость, ресурсоэффективность
1. Selenide - фреймворк для написания автотестов, премущества: локаничные, стабильные  и простые тесты
1. Gradle - для сборки проекта, премущества: автоматизация сборки, тестирования и развертывания проектов.
1. Настройка CI в appveyor для GitHub, премущества: непрерывная интеграция, позволяет выявить ошибки при сборке проекта
1. Настройка Reporting allure для предоставления отчётов заинтересованным лицам, премущества: подробные сценарии тестов, с приложением скриншотов, графиков


## Перечень необходимых разрешений, данных и доступов.
1. получить разрешение на выполнение таких работ у владельца сайта
1. доступ к базе данных
1. доступ к API сайта


## Перечень и описание возможных рисков при автоматизации.
1. изменение интерфейса(изменили названия кнопок, вкладок и т.д.)
1. неустойчивость среды(изменения в окружении, такие как обновления браузеров или операционных систем)
1. отсутствие навыков в команде (смена коллектива)


## Перечень необходимых специалистов для автоматизации.
1. Автотестировщик на Java


## Интервальная оценка с учётом рисков в часах.
24 рабочих часа (3 рабочих дня)
