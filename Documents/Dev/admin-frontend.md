# Админка

### Мета-информация

Разработчик: Александр Мураев

Через админку в приложении будет добавляться и модерироваться контент 

### Техническое задание

1) Сущности и API смотри в `content-service.md` (прежде всего стоит прочитать этот документ)

2) Дизайн реализовать при помощи Bootstrap на свое усмотрение, по мере возможностей согласовывать с Александром Кудрявцевым. Рекомендую найти шаблон с уже готовой админкой и реализовывать, обращаясь к ней

3) Страницы
- "Вход" содержит форму для логина
- "Навыками" содержит таблицы с навыкам, поисковой строкой и кнопкой "Добавить". По нажатию на строчку таблицу открывается модальное окно для редактирования "навыка". По нажатию на "Добавить" открывается модальное окно для создания "навыка"
- "Категории навыков" аналогична "Навыкам"

Страницы "Проекты" и "Профили" позволяют искать соответствующие сущности и просматривать их. В текущей итерации функционал модерации их не предусмотрен 

2) Технологии

Админку реализовать при помощи React, Redux и axios, а также TypeScript, ReduxToolkit (опционально)