# Todo: практика 7 ноября

Приложение с двумя экранами: список задач и добавление задачи.
Свайп показывает действие удаления, которое открывает диалог подтверждения.
Пустое название не сохраняется; данные хранятся в памяти.

Проверено на Flutter 3.35.7 / Dart 3.9.2. Для запуска нужен Chrome.

## Запуск

```bash
flutter pub get
flutter run -d chrome
```

## Проверка

```bash
flutter analyze
flutter test
flutter test test/package_check.dart test/behavior_check.dart
```

Вывод проверок находится в `submission/`.

## Демонстрация

- [Видео: добавление, свайп, отмена и подтверждение удаления](submission/demo.mp4).
- [Список задач](submission/screenshots/list.png).
- [Экран добавления](submission/screenshots/add.png).
- [Диалог удаления](submission/screenshots/delete.png).
