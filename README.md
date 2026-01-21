# SYNTRISE CORTEX

Центр управления экосистемой Syntrise.

## Деплой на Vercel

1. Создай новый проект в Vercel
2. Import из этой папки
3. Домен: `cortex.syntrise.com`

## Supabase Config

Добавь в Authentication → URL Configuration → Redirect URLs:
```
https://cortex.syntrise.com
```

## Доступ

Только пользователи с `tier = 'owner'` в таблице `user_limits` могут войти.
