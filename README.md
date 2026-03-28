# Import Control Platform

Операционная платформа для управления импортом продукции из Европы в Казахстан.

## 🚀 Быстрый деплой на GitHub Pages (бесплатно)

### Шаг 1: Создай репозиторий
1. Зайди на https://github.com/new
2. Название: `import-control`
3. Public (обязательно для бесплатного GitHub Pages)
4. Нажми **Create repository**

### Шаг 2: Загрузи файлы
1. На странице репозитория нажми **uploading an existing file**
2. Перетащи файл `index.html` (переименуй `import-control.html` → `index.html`)
3. Нажми **Commit changes**

### Шаг 3: Включи GitHub Pages
1. Зайди в **Settings** → **Pages** (в левом меню)
2. Source: **Deploy from a branch**
3. Branch: **main** / **root**
4. Нажми **Save**

### Шаг 4: Готово!
Через 1-2 минуты сайт будет доступен по адресу:
```
https://ТВОЙ-USERNAME.github.io/import-control/
```

## 📱 Что работает

- ✅ Dashboard с KPI, фильтрами, поиском
- ✅ 14 этапов с подэтапами и блокировками
- ✅ CRUD: поставки, SKU, расходы, задачи, риски, документы, каналы
- ✅ Сценарный анализ (3 режима)
- ✅ Склад и приёмка
- ✅ Запуск продаж (чеклист)
- ✅ Аналитика с графиками (Recharts)
- ✅ Согласования (approval flow)
- ✅ Аудит изменений
- ✅ Уведомления
- ✅ Экспорт JSON
- ✅ localStorage — данные сохраняются между сессиями
- ✅ Мобильная адаптация
- ✅ Тёплый bakery-дизайн

## 🔧 Технологии

- React 18 (CDN)
- Recharts (графики)
- Babel (JSX в браузере)
- localStorage (persistence)
- Чистый CSS (no frameworks)
- Один HTML файл — zero dependencies

## 📋 Следующий этап

Переход на Next.js + Supabase + Vercel:
- Реальная БД (PostgreSQL через Supabase)
- Авторизация
- Мульти-юзер
- Загрузка файлов
- Realtime уведомления
- Полноценный API

Все артефакты для этого уже готовы:
- `prisma-schema.prisma` — 38 таблиц
- `import-control-backend.tar.gz` — backend (seed, API, сервисы, типы, валидация)
