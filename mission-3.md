# Задание 3. Управление группами
1. Создать контроллер для групп с необходимыми методами:
    - список
    - создание
    - редактирование
    - удаление

2. Создать маршруты для методов
3. Организовать структуру шаблонов:
    - layouts
        - app.blade.php - базовый шаблон
    - includes
        - header.blade.php
        - footer.blade.php
    - groups
        - index.blade.php
        - create.blade.php
        - edit.blade.php
        - form.blade.php
        - show.blade.php

**Примечание:**
- использовать FormRequest для валидации
- использовать пагинацию для списков
- использовать именованные роуты
- установить Laravel Debugbar и Laravel Telescope для отладки

### Изучить:
- [Laravel Best Practices](https://github.com/alexeymezenin/laravel-best-practices#follow-laravel-naming-conventions)
- [Routing](https://laravel.com/docs/8.x/routing)
- [Controllers](https://laravel.com/docs/8.x/controllers)
- [Validation](https://laravel.com/docs/8.x/validation)
- [Views](https://laravel.com/docs/8.x/views)
- [Blade](https://laravel.com/docs/8.x/blade)

---
[2. Laravel, миграции и модели](mission-2.md) ← | → [4. Управление студентами, предметами и оценками](mission-4.md)
