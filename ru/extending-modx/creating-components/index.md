---
title: "Создание компонентов"
translation: "extending-modx/creating-components"
---

Это занятие открывает новый раздел на сайте, где будут публиковаться обучающие курсы или руководства.

В данном курсе от [Василия Наумкина](https://github.com/bezumkin) мы будем писать не абы что, а нужный и полезный компонент рассылок по юзерам сайта, который мы потом подарим всем пользователям MODX.

## Приблизительный план первого курса:

- [Настройка рабочего места и IDE PhpStorm](extending-modx/creating-components/customize-the-workplace/)
- [Разбор структуры компонента, зачем нужны assets, core и остальные?](extending-modx/creating-components/component-structure/)
- [Основы Git и первый коммит заготовки компонента на Github](extending-modx/creating-components/git-basics/)
- [Продумываем логику работы, определяем схему и модель таблицы в БД](extending-modx/creating-components/work-logic/)
- [Первые наброски логики, собираем и устанавливаем альфа-версию пакета](extending-modx/creating-components/package-build/)
- [Интерфейс админки на ExtJS. Создаём группы рассылок и подписываем на них пользователей.](extending-modx/creating-components/extjs-widgets/)
- [Интерфейс админки на ExtJS. Создаём рассылку и привязываем её к группе.](extending-modx/creating-components/subscription-table/)
- Проверяем работу нашего интерфейса, пробуем что-то разослать.
- Фронтент. Сниппет вывода доступных подписок пользователю.
- Фронтент. Работа с подпиской и отпиской от рассылки.
- Тестирование, сборка пакета, окончание работ.

Говорю сразу — список неточный, все может 10 раз поменяться, так как мы пишем новый компонент, а не разбираем существующий.

Еще прошу вас прямо сейчас [загрузить PhpStorm](http://www.jetbrains.com/phpstorm/download/). Демо версия работает без ограничения функциональности целый месяц, и этого времени вам хватит, чтобы понять, стоит ли его покупать.
Конечно, все инструкции и примеры я буду приводить именно для этой IDE.

Помимо этого, подумайте сразу о том, где вы будете разрабатывать компонент? На своем локальном компьютере, в виртуальной машине или на хостинге?

Думаю, можно попробовать использовать и [бесплатный аккаунт на MODXcloud](https://modxcloud.com/signup/lab-account.html).
