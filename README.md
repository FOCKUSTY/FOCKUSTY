<h1 align="center">Backend-разработчик (Full Stack) | Фокус на высоконагруженные системы</h1>

<div align="center">

![banner](./assets/img/TheVoid.Banner.png)

Русский | [English](./langs/README.en.md)

</div>

## Обо мне

Увлечённый backend-разработчик с опытом построения отказоустойчивых и масштабируемых серверных приложений. Глубоко погружён в архитектуру API, оптимизацию баз данных, асинхронную обработку и DevOps-практики. При этом имею сильные компетенции во фронтенд-разработке, что позволяет мне эффективно выстраивать взаимодействие между клиентом и сервером и создавать полноценные full-stack решения.

**Текущий фокус:** Высоконагруженные распределённые системы, микросервисная архитектура, оптимизация запросов к БД, real-time взаимодействие (WebSocket, Message Queues), мониторинг и observability.

---

## Стек технологий и инструменты

### Языки и платформы
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Бэкенд-фреймворки
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

### Базы данных и очереди
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Фронтенд
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### Инструменты разработки и DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white)

### Мониторинг и observability
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)

---

## Ключевые проекты

### BAD Architecture – Продакшен-готовый шаблон для NestJS  
**Стек:** NestJS, TypeScript, MongoDB/PostgreSQL, Passport.js, Docker, Swagger, Sentry  
**Описание:** Модульная бэкенд-архитектура с готовой системой аутентификации (OAuth 2.0, JWT), централизованной обработкой ошибок, строгой типизацией, валидацией окружения и автоматической документацией API. Включает кастомный CLI для генерации кода и best practices для построения масштабируемых приложений.  
**Роль:** Архитектор и основной разработчик.  
[→ Репозиторий](https://github.com/Lazy-And-Focused/BAD-template)

### Real-time мессенджер – Полноценное full-stack приложение  
**Стек:** NestJS, Socket.io, PostgreSQL, Redis, Next.js, Tailwind  
**Описание:** Серверная часть мессенджера с поддержкой личных и групповых чатов, доставкой сообщений в реальном времени, управлением сессиями и очередями задач. Реализована пагинация сообщений, кэширование (Redis), авторизация через Google OAuth 2.0 и JWT.  
**Роль:** Разработка бэкенда, проектирование API, интеграция WebSocket.  
[→ Бэкенд](https://github.com/The-Void-Community/tvc-hat/tree/main/apps/backend) | [→ Фронтенд](https://github.com/The-Void-Community/tvc-hat/tree/main/apps/frontend)

### Кастомный UI-кит – Библиотека компонентов  
**Стек:** React, TypeScript, Storybook, Vite, Tailwind  
**Описание:** Библиотека переиспользуемых компонентов с подробной документацией. Стандартизирует дизайн между проектами, ускоряет разработку и улучшает UX.  
**Роль:** Автор и архитектор UI-кита.  
[→ Репозиторий](https://github.com/The-Void-Community/tvuikit)

### Инструменты и библиотеки для Node.js

- **fock-logger** – продвинутая библиотека для структурированного логирования в Node.js-приложениях. Поддерживает multiple транспорты, уровни логирования, форматы (JSON, pretty), интеграцию с Sentry.  
  [→ Репозиторий](https://github.com/FOCKUSTY/fock-logger)

- **passworder** – CLI-менеджер паролей с шифрованием на базе Node.js. Позволяет безопасно хранить и извлекать пароли, используя мастер-пароль и современные криптоалгоритмы.  
  [→ Репозиторий](https://github.com/FOCKUSTY/passworder)

- **fouter** – декларативное описание HTTP-API с автоматической генерацией TypeScript-типов для клиента и сервера. Упрощает поддержку type-safety между бэкендом и фронтендом.  
  [→ Репозиторий](https://github.com/FOCKUSTY/fouter)

- **fbit-field** – TypeScript-библиотека для эффективной работы с битовыми полями (полезно для низкоуровневых оптимизаций и работы с флагами).  
  [→ Репозиторий](https://github.com/FOCKUSTY/fbit-field)

[Все репозитории →](https://github.com/FOCKUSTY?tab=repositories)

---

## Статистика GitHub

<div align="center">

![Детали профиля](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=FOCKUSTY&theme=github_dark)

![Языки по репозиториям](http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=FOCKUSTY&theme=github_dark)
![Самые используемые языки](https://github-readme-stats.vercel.app/api/top-langs/?username=FOCKUSTY&layout=compact&theme=github_dark)

![Статистика GitHub](https://github-readme-stats.vercel.app/api?username=fockusty&show_icons=true&theme=github_dark)
![Стрик коммитов](https://github-readme-streak-stats.herokuapp.com?user=FOCKUSTY&theme=github-dark&hide_border=true&border_radius=20&date_format=M%20j%5B%2C%20Y%5D)

</div>

---

## Связь со мной

<div align="center">

| Платформа | Ссылка | Для чего |
|:---|:---|:---|
| **Telegram** | [@fockusty](https://t.me/fockusty) | Основное общение |
| **VK** | [fockusty](https://vk.com/fockusty) | Социальная сеть |
| **Discord** | `#FOCKUSTY` | Игры и сообщества |
| **Bluesky** | [@fockusty](https://bsky.app/profile/fockusty.laf-team.ru) | Технические обсуждения |

</div>

---

## В поиске

- Стажировки/младшей позиции как Backend или Fullstack-разработчик (с фокусом на бэкенд)
- Коллаборации над open-source проектами, связанными с бэкенд-инфраструктурой, базами данных, highload, а также над full-stack приложениями
- Возможностей поработать над распределёнными системами, real-time приложениями или сервисами с высокой нагрузкой

<div align="center">

![Футер-баннер](./assets/img/TheVoid.TALL.jpg.png)

</div>
