# Sip Happens Café — Feedback Widget ☕️

Навчальний React-застосунок для збору відгуків від відвідувачів кав'ярні **Sip Happens Café**. Проєкт розроблено з використанням **React**, **TypeScript**, **Vite** та **CSS Modules**.

## Функціонал

- **Голосування**: Можливість залишити відгук трьох типів — _Good_ , _Neutral_ , _Bad_ .
- **Розрахунок статистики**:
- Загальна кількість відгуків (`Total`).
- Відсоток позитивних відгуків (`Positive feedback`).
- **Скидання даних**: Кнопка `Reset` для повного обнулення збережених голосів (відображається лише за наявності голосів).
- **Умовний рендеринг**: За відсутності відгуків показується сповіщення `No feedback yet`.

---

## Технологічний стек

- **React 18** (Компонентний підхід, хуки `useState`)
- **TypeScript** (Типізація пропсів та стану)
- **Vite** (Збирач та dev-сервер)
- **CSS Modules** (Ізольовані стилі для кожного компонента)
- **modern-normalize** (Нормалізація базових стилів браузера)

---

## Структура проєкту

```text
02-react-cafe/
├── src/
│   ├── components/
│   │   ├── App/
│   │   │   ├── App.tsx
│   │   │   └── App.module.css
│   │   ├── CafeInfo/
│   │   │   ├── CafeInfo.tsx
│   │   │   └── CafeInfo.module.css
│   │   ├── Notification/
│   │   │   ├── Notification.tsx
│   │   │   └── Notification.module.css
│   │   ├── VoteOptions/
│   │   │   ├── VoteOptions.tsx
│   │   │   └── VoteOptions.module.css
│   │   └── VoteStats/
│   │       ├── VoteStats.tsx
│   │       └── VoteStats.module.css
│   ├── types/
│   │   └── votes.ts
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

---

## Локальний запуск

1. **Клонувати репозиторій**:

   ```bash
   git clone https://github.com/anhelov-y/02-react-cafe.git
   cd 02-react-cafe
   ```

2. **Встановити залежності**:

   ```bash
   npm install
   ```

3. **Запустити сервер розробки**:

   ```bash
   npm run dev
   ```

4. **Відкрити у браузері**:
   Перейдіть за адресою `http://localhost:5173/`.
