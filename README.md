# 🐾Cats Dataset — Power BI Dashboard

Интерактивный дашборд на основе синтетического датасета (1000 кошек). 
Анализ по породам, возрасту, весу, окрасу и полу.

---

## 📋 Данные

| Column             | Type    | Description               |
|--------------------|---------|---------------------------|
| `Cat_ID`           | Integer | Уникальный ID 🐾          |
| `Breed`            | Text    | Порода кошки              |
| `Age_Years`        | Decimal | Возраст (годы)            |
| `Weight_kg`        | Decimal | Вес (кг) ⚖️               |
| `Color`            | Text    | Окрас / паттерн шерсти    |
| `Gender`           | Text    | Пол животного             |
| `Age_Group`        | Text    | Kitten 🐱 / Adult 😺 / Senior 🐈 |
| `Weight_Category`  | Text    | Light / Medium / Heavy    |

---

## 🧮 DAX-меры

- `Total_Cats` — общее количество кошек
- `Avg_Age` — средний возраст
- `Avg_Weight` — средний вес
- `Kittens_Count` — количество котят 🐱

---

## 🚀 Как открыть

1. Скачай репозиторий (**Code → Download ZIP**)
2. Открой `pbix/cats_dashboard.pbix` в Power BI Desktop

---

## 🔗 Источник данных

[Cats Dataset by Waqar Ali, Kaggle](https://www.kaggle.com/datasets/waqi786/cats-dataset)

---

## 🐾 Роль AI

AI (Алиса AI, Яндекс) — мой **ментор и второй пилот** на этом проекте 🐱‍👤

Помогал с DAX-формулами, структурой дашборда и оформлением документации. 
Все решения по дизайну, данным и финальной сборке — мои. 
AI был отличным ко-пилотом, который вовремя подсказывал нужную формулу и напоминал про типы данных 🐾

Проверено: дашборд не пугает котиков, срезы работают, KPI не убегают ✨

---

