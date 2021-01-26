# EasyEPLANner - Open Source

### Репозиторий
Данный репозиторий (хранилище) представляет собой проект с открытым исходным кодом - EasyEPLANner. Мы не только работаем над проектом, но и решаем различные задачи связанные с жизнью и развитием проекта.

### EasyEPLANner

![](../user_manual/images/EasyEPLANnerPreview.png)

Надстройка EasyEPLANner разработана как Add-In к EPLAN, на данный момент используется версия EPLAN 2.9. Надстройка используется при разработке проектов в EPLAN и позволяет автоматизировать работу инженера по автоматизации, а так же инженера-программиста, который описывает проект на языке программирования LUA.

С помощью EasyEPLANner описываются технологические объекты (Танк, Бойлер и др.), операции этих объектов, шаги операций, устанавливаются ограничения для операций, а так же множество других свойств технологического объекта. В конечном итоге, EasyEPLANner генерирует LUA файлы, которые загружаются в контроллер. В данный момент поддерживаются контроллеры следующих производителей:

1. [Phoenix Contact - PLCNext](https://github.com/plcnext);
2. [WAGO - PFC200](https://github.com/WAGO).

### Пользовательская документация
По [этой](docs/user_manual/readme.md) ссылке вы можете найти последнюю версию пользовательской документации к проекту.

### Содействие (Contributing)
Если вы хотите посодействовать в разработке нашего проекта, то перед началом ознакомьтесь с тем, [как лучше всего это сделать](docs/contributing.md).

### Обратная связь (Feedback)
Если вы хотите связаться с нами, можно использовать несколько способов:
* [Google группа](https://groups.google.com/forum/#!forum/EasyEPLANner);
* Канал в [Slack](https://slack.com) - EasyEPLANner.slack.com.

### Нормы поведения (Code of conduct)
Мы [используем](docs/CODE_OF_CONDUCT.md) стандартные нормы поведения (общения), которые предоставляет сервис GitHub.

### Правила кодирования (Code style)
Для разработки используется язык программирования - C#, а так же Lua. У нас есть [собственный набор соглашений](docs/codestyle.md), которых нужно придерживаться что бы код был удобным и читабельным.

### Лицензия
Проект лицензирован под [MIT](LICENSE.txt) лицензией.