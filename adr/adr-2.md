# ADR-2: Фронтенд-стек

## Статус
**Принято**

## Контекст:
Требуется кроссплатформенное решение для:
- Мобильных приложений (iOS/Android)
- Веб-интерфейса для партнеров и администрации

## Решение:
1. Мобильное приложение: React Native + TypeScript
2. Веб-интерфейс: Next.js 14 + Tailwind CSS

Обоснование:
- Единая кодовая база для мобильных платформ
- TypeScript для типобезопасности
- Server-side rendering в Next.js для SEO
- Tailwind для единого дизайн-системы

## Последствия:
Плюсы:
- Сокращение затрат на разработку
- Совместимость с UI-китом вуза

Минусы:
- Требуется экспертиза по React Native
- Необходимость поддержки двух платформ

## Альтернативы:
- **Native разработка**: Потребовала бы 2 команды для iOS/Android (2x бюджета).
- **React Web**: Не решает мобильные задачи.