# FileSorter

#### Build Container
`docker-compose build`

#### Run Container
`docker-compose run cpp`

### Run Project
`make run`

### Запууск тестов
`make run-test`

### Контейнер
Контейнер ограничен на 500 МБ памяти.

### О репозитории
Проект представляет собой построчную сортировку файлов вне зависимости от размера ( можно менять буффер оперативной памяти, по дефолту стоит тестовый размер 1000 )
, а также генератор файлов с параметрами - длина строки и количество строк, помимо этого имеет возможность генерировать только числовые строки.

### Примеры
Примеры сгенерированных и отсортированных фалйов можно найти в диреткории GeneratedData


