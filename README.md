# Redux Base

## Что должно быть сделано:

1. Копировать ветку `main` исходного репозитория и создать отдельную ветку `redux-base` для этого задания.
2. Сконфигурировать store, и обернуть компоненты в `<Provider />` в `App.tsx`.
3. Реализовать reducer для store с `ADD_TODO`, `REMOVE_TODO` и `TOGGLE_TODO` с использованием массива из объектов `Todo`.
3. Реализовать экшены `addTodo` , `removeTodo` и `toggleTodo` и их вызов для компонентов `<TodoForm />` и `<TodosListItem />`, экшены должны быть реализованы без асинхронной логики.
4. Для конфигурации store использовать устаревшую функцию `createStore`.


Backend для этого задания не требуется, версии пакетов обновлять не нужно, устанавливать дополнительно пакеты не нужно.

### Теория
* [Redux Base (eng)](https://handsonreact.com/docs/redux)
* [Redux & TypeScript (eng)](https://handsonreact.com/docs/redux-typescript)
* [Основы Redux (ru)](https://max-frontend.gitbook.io/redux-course-ru-v2/sozdanie/osnovi-redux-teoriya)


## Копирование репозитория todo-app-redux.

- Создайте новый репозиторий на GitHub: `todo-app-redux`
- Клонируйте этот репозиторий: `$ git clone https://github.com/shopot/todo-app-redux.git`
- Перейдите в директорию: `$ cd todo-app-redux`
- Удалите `.git` директорию: `$ rm -rf .git`
- Создайте пустой Git репозиторий : `$ git init`
- Подключите удаленный репозиторий: `$ git remote add origin https://github.com/your_nickname/todo-app-redux.git`
- Переименуйте ветку: `$ git branch -M main`
- Добавьте существующие файлы в репозиторий: `$ gti add .`
- Выполните первый коммит: `$ git commit -m "init: start project"`
- Отправьте изменения в GitHub : `$ git push -u origin main`

## Установка и запуск

- Использовать `node 18.x` или выше.

```shell
# Install the dependencies
$ npm install

# Start Vite development server
$ npm run dev

# Build production
$ npm run build

# Preview production after build production
$ npm run preview

# Start linting
$ npm run lint
```
