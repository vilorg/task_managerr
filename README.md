# Task Manager

Task Manager — это приложение на Flutter для управления задачами с поддержкой добавления, редактирования и удаления задач. Приложение поддерживает локализацию, светлую и тёмную темы.

## Установка

1. Убедитесь, что у вас установлены Flutter и Dart.

2. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/vilorg/task_manager.git
   ```
3. Перейдите в папку проекта:
   ```bash
   cd task_manager
   ```
4. Установите зависимости:
   ```bash
   flutter pub get
   ```
5. Установите локали:
   ```bash
   flutter gen-l10n
   ```

## Запуск приложения

1. Запустите эмулятор или подключите физическое устройство.
2. Выполните команду:
   ```bash
   flutter run
   ```

## Функционал

- Добавление новой задачи
- Редактирование существующей задачи
- Удаление задачи
- Установка важности задачи (Нет, Низкая, Высокая)
- Установка дедлайна задачи
- Поддержка локализации (пока только русский)
- Светлая и тёмная темы

### На момент первой итерации сделано:

- Составлена структура проекта
- Сделаны стили
- Добавлены базовые экраны
- Логика сейчас в состоянии "заглушка"

## Структура проекта

lib/
├── core/
│ ├── logger.dart
│ └── theme.dart
├── features/
│ ├── task/
│ │ ├── data/
│ │ ├── domain/
│ │ │ └── todo_model.dart
│ │ └── presentation/
│ │ ├── pages/
│ │ │ ├── add_edit_task_page.dart
│ │ │ └── home_page.dart
│ │ ├── widgets/
│ │ │ ├── persistent_header.dart
│ │ │ └── task_item.dart
└── main.dart

## Скриншоты

![Главный экран](https://raw.githubusercontent.com/vilorg/task_manager/commit/main.png)
![Экран добавления задачи](https://raw.githubusercontent.com/vilorg/task_manager/commit/add_task.png)

## Логирование

Для логирования используется пакет `logger`. Логи записываются для различных действий, таких как добавление, редактирование, удаление задач и установка дедлайна.

## Ссылка на Apk

- [Release Apk](https://github.com/vilorg)

## Авторы

- [Dmitry Petrov](https://github.com/vilorg)
