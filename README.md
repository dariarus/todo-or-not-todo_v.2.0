### ToDo-лист "ToDo-or-not-ToDo". Версия 2.0

#### Описание и функциональность: 
Небольшая приложение для управления задачами. 
* Через форму можно добавить новую задачу, а по желанию - отметить ее как важную и добавить описание. 

* Задачи можно фильтровать по статусу: доступен просмотр всех задачи, невыполненных и выполненных. У каждой задачи можно поменять статус: 

а) невыполненную можно пометить выполненной - это действие доступно как из списка всех задач, так и из списка невыполненных;

б) выполненную задачу можно вернуть обратно в список невыполненных - действие так же доступно из списка всех задач и из списка выполненных.

* Любую задачу можно удалить по клику на крестик. 

* Задачи можно сортировать перетаскиванием.

*Новый функционал и другие изменения в версии 2.0*: 
- возможность поиска задач по имени/описанию. Поле для поиска появляется, только если создана хотя бы одна задача.
- возможность отмечать задачи как важные. 
Это можно сделать как при создании задачи, так и нажав на звездочку справа от названия уже созданной задачи
- возможность редактировать существующие задачи.
Для этого нужно нажать на карандашик справа от названия. 
Откроется попап, в котором можно изменить название, описание, поставить или снять отметку "Выполненная" и поставить или снять отметку "Важная". 
- Теперь для каждой задачи отображается дата добавления ее в список.
Если задача отмечена как выполненная, то отображается дата выполнения.
- возможность сортировать созданные задачи по названию, важности или дате добавления/выполнения.
Область сортировки открывается в виде "аккордеона" по нажатию на иконку "Настройки", которая появляется справа от списка фильтров, если добавлена хотя бы одна задача.

а) По названию: доступна сортировка по алфавиту от А до Я и от Я до А.

б) По важности: можно показывать сначала важные или сначала неважные задачи

в) По дате: доступно два варианта. Первый - по дате добавления задачи в список; применить можно из списка всех задач и из списка невыполненных. Второй - по дате выполнения; применяется только к списку выполненных задач.

Одновременно доступен только один вид сортировки.

Если происходят любые изменения в списке задач, сортировка не сбрасывается.

- возможность сохранять созданные задачи в localStorage и не терять список при перезагрузке страницы.
В хранилище попадают также и все изменения, произведенные с уже созданными задачами.
А удаленные задачи больше не будут отображаться на странице.
- в приложение добавлен стейт-менеджер MobX.

#### Используемые технологии: 
* React
* TSX
* React Hook
* MobX
* react-dnd
* flexbox
* БЭМ
* JavaScript
* TypeScript
* Vite

#### В разработке: 
* возможность указать дату дедлайна при создании или редактировании задачи;
* возможность сортировать задачи по ближайшей дате дедлайна;
* возможность подтверждать действие при удалении задачи;
* адаптив.

#### Инструкция по запуску приложения:

1). Клонировать репозиторий :
```
git clone git@github.com:dariarus/todo-or-not-todo_v.2.0.git
```

2). Перейти в папку с проектом:
```shell
cd todo-or-not-todo_v.2.0
```

3). Запустить приложение в режиме разработки:
```shell
npm install
npm run dev
```

4). Открыть приложение в браузере по адресу:
http://127.0.0.1:3000/toDo-or-not-toDo/

*Ссылка на страницу приложения на GitHub Pages*: [ToDo-2]()
