# 🐠 Акватеррон v2.0

> Полнофункциональное приложение для управления аквариумами и террариумами

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Active-brightgreen)](https://AquaTerraPro.github.io/aquaterron-app/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-18.2.0-61dafb.svg)](https://reactjs.org/)

## 🌐 Демо

**[🚀 Открыть приложение](https://AquaTerraPro.github.io/aquaterron-app/)**

## ✨ Основные возможности

### 🏠 **Управление системами**
- Создание и управление аквариумами, террариумами, палюдариумами
- Мониторинг параметров воды и микроклимата
- Отслеживание состояния биосистем

### 🧮 **Умные калькуляторы**
- **Биозагрузка** - оптимальное количество рыб
- **Подмена воды** - расчет объемов и частоты
- **Кормление** - рекомендации по рациону

### 📚 **База знаний**
- **50+ видов рыб** с характеристиками совместимости
- **20+ видов рептилий** для террариумов
- **30+ видов растений** с требованиями к уходу

### 📅 **Планирование и напоминания**
- Календарь событий и задач
- Автоматические напоминания о подмене воды
- Планировщик кормления и обслуживания

### 📊 **Аналитика и статистика**
- Графики изменения параметров
- История всех действий
- Анализ здоровья системы

### 🏆 **Система достижений**
- Прогресс и уровни пользователя
- Мотивационные награды
- Отслеживание опыта

## 🚀 Быстрый старт

### Локальная разработка

```bash
# Клонирование репозитория
git clone https://github.com/AquaTerraPro/aquaterron-app.git
cd aquaterron-app

# Установка зависимостей
npm install

# Запуск в режиме разработки
npm start

# Открыть http://localhost:3000
### Деплой на GitHub Pages

```bash
# Установка зависимости для деплоя
npm install --save-dev gh-pages

# Деплой
npm run deploy
```

## 📱 Скриншоты

| Главная страница | Детали системы | Калькуляторы |
|---|---|---|
| ![Home](docs/screenshots/home.png) | ![System](docs/screenshots/system.png) | ![Calculators](docs/screenshots/calculators.png) |

| База знаний | Статистика | Календарь |
|---|---|---|
| ![Database](docs/screenshots/database.png) | ![Stats](docs/screenshots/stats.png) | ![Calendar](docs/screenshots/calendar.png) |

## 🛠 Технологии

- **Frontend:** React 18, Tailwind CSS
- **Icons:** Lucide React
- **Deployment:** GitHub Pages, GitHub Actions
- **PWA:** Service Worker, Web App Manifest

## 📊 Структура проекта

```
aquaterron-app/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── AquaTerronApp.js     # Главный компонент
│   ├── index.js             # Точка входа
│   └── index.css            # Стили
├── .github/
│   └── workflows/
│       └── deploy.yml       # CI/CD
├── docs/
│   └── screenshots/         # Скриншоты
└── README.md
```

## 💾 Импорт/Экспорт данных

Приложение поддерживает полный экспорт и импорт всех пользовательских данных в JSON формате:

- ✅ Список всех биосистем
- ✅ События календаря
- ✅ Журнал действий
- ✅ Заметки и настройки
- ✅ Прогресс и достижения

## 🤝 Участие в разработке

1. Форкните проект
2. Создайте ветку для новой функции (`git checkout -b feature/amazing-feature`)
3. Закоммитьте изменения (`git commit -m 'Add amazing feature'`)
4. Отправьте в ветку (`git push origin feature/amazing-feature`)
5. Откройте Pull Request

## 📝 Лицензия

Этот проект лицензирован под MIT License - см. файл [LICENSE](LICENSE).

## 📧 Контакты

- **GitHub Issues:** [Создать баг-репорт или предложение](https://github.com/YOUR-USERNAME/aquaterron-app/issues)
- **Discussions:** [Обсуждения и вопросы](https://github.com/YOUR-USERNAME/aquaterron-app/discussions)

---

<div align="center">
  
**[⭐ Поставьте звезду, если проект понравился!](https://github.com/YOUR-USERNAME/aquaterron-app)**

Сделано с ❤️ для сообщества аквариумистов

</div>
```

## 3️⃣ **Команды для загрузки**

```bash
# Инициализация локального репозитория
git init

# Добавление файлов
git add .

# Первый коммит
git commit -m "🐠 Initial commit: Aquaterron v2.0 - Full-featured aquarium management app

✨ Features:
- 🏠 Multi-system management (aquariums, terrariums, paludariums)
- 🧮 Smart calculators (bioload, water change, feeding)
- 📚 Extensive species database (fish, reptiles, plants)
- 📅 Event calendar with reminders
- 📊 Advanced analytics and statistics
- 🏆 Achievement system with gamification
- 👥 Community features and expert consultations
- 💾 Full data export/import capabilities
- 📱 PWA support with responsive design
- 🎨 Modern dark theme with gradients"

# Подключение к GitHub репозиторию
git remote add origin https://github.com/YOUR-USERNAME/aquaterron-app.git

# Отправка кода
git push -u origin main
```

## 4️⃣ **Настройка GitHub Pages**

1. Перейдите в **Settings** репозитория
2. Найдите раздел **Pages**
3. Source: **Deploy from a branch**
4. Branch: **gh-pages** (создастся автоматически после первого деплоя)
5. Нажмите **Save**

## 5️⃣ **Первый деплой**

```bash
# Установка gh-pages локально
npm install --save-dev gh-pages

# Деплой (займет 2-3 минуты)
npm run deploy
```

После успешного деплоя приложение будет доступно по адресу:
`https://YOUR-USERNAME.github.io/aquaterron-app/`
