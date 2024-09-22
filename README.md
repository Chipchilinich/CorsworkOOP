# Курсовой проект по модулю ООП

Приложение получает информацию о вакансиях с платформы hh.ru в России, сохраняет ее в файл и позволяет работать с ней: добавлять, фильтровать, удалять.

## Описание проекта

   Проект включает модули

 - Модуль (vacancy) - служит для работы с вакансиями,поддерживает метод сравнения вакансий между собой по зарплате и
метод валидирования данных, которыми инициализируются его атрибуты.
 - Модуль (vacancy_api) - служит для работы работы с платформой hh.ru.Реализованные в нем классы умеют подключаться к API и получать вакансии
 - Модуль (vacancy_storage) - содержит методы для добавления вакансий в файл, получения данных из файла по указанным критериям и удаления информации о вакансиях.


## Установка:

1. Клонируйте репозиторий:
```
git clone https://github.com/IvanRas/coursework_2
```
2. Установите зависимости:
```
poetry install
```
## Использование:

Проект содержит модуль main, служащий для взаимодействовать с пользователем через консоль

## Тесты:
 - Для тестирования используются Mock и patch
 - Программа покрыта тестами на 81%
