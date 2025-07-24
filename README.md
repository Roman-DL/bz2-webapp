# 🎯 БЗ 2.0 WebApp

**WebApp компоненты для системы База Знаний 2.0**

## 📋 Формы

### Регистрация пользователей
- **URL:** [forms/registration.html](forms/registration.html)
- **Назначение:** Регистрация новых консультантов и спонсоров
- **Интеграция:** n8n webhook → Google Sheets → Telegram Admin
- **Статус:** ✅ Production Ready

## 🔗 Интеграция

- **Webhook:** `https://n8napps.online/webhook/bz2-user-registration`
- **n8n Workflow:** `BZ2_User_Registration.json`
- **Data Storage:** Google Sheets "БЗ 2.0 Registrations"
- **Admin Notifications:** Telegram

## 🚀 Развертывание

Форма автоматически развертывается через GitHub Pages при push в main branch.

**Система обслуживает 1000+ консультантов по питанию.**