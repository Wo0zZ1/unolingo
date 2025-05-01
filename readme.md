<h1 align="center"><b>🌐 Unolingo 🎓</b></h3>

<p align="center"><i>Изучайте языки легко и весело!</i></p>
<hr />

**Unolingo** — это интерактивное мобильное приложение для изучения иностранных языков в игровой форме. Проект разработан в рамках учебной практики в вузе и сочетает в себе современные технологии с удобным интерфейсом.

## 🔥 **Ключевые особенности**

- 🎮 **Геймификация обучения** — система уровней, достижений и наград.
- 📚 **Разнообразные упражнения** — словарные карточки, аудирование, грамматические тесты.
- 📊 **Таблица рейтинга** — соревнуйтесь с другими пользователями.
- 🌍 **Поддержка нескольких языков** — английский, испанский, французский и другие.
- 🔄 **Синхронизация между устройствами** — ваш прогресс сохраняется в облаке.

## 🛠 **Технологический стек**

### **Frontend**

- [React Native](https://reactnative.dev/) + [Expo](https://expo.dev/go) — кроссплатформенная разработка.
- [Axios](https://axios-http.com/ru/) — работа с API.
- [zustand](https://zustand-demo.pmnd.rs/) - state-менеджер
- [Async storage](https://www.npmjs.com/package/@react-native-async-storage/async-storage) — работа с локальным хранилищем.
- [TypeScript](https://www.typescriptlang.org/) — статическая типизация.

### **Backend**

- [NestJS](https://nestjs.com/) — масштабируемый backend на Node.js.
- [Bcrypt](https://www.npmjs.com/package/bcrypt) — хеширование паролей.
- [JWT](https://www.npmjs.com/package/@nestjs/jwt) — аутентификация.

### **База данных**

- [PostgreSQL](https://www.postgresql.org/) — реляционная СУБД для хранения данных.
- [PrismaORM](https://www.prisma.io/) — работа с БД.

## 🚀 **Установка и запуск**

### **1. Клонирование репозитория с подмодулями**

```bash
git clone --recurse-submodules https://github.com/Wo0zZ1/unolingo.git
cd unolingo
```

#### 💡 **`TIP`**: Если репозиторий был склонирован без подмодулей, выполните:

```bash
git submodule update --init --recursive
```

### **2. Настройка Backend**

```bash
cd backend
yarn
```

#### 💡 **`TIP`**: Если у вас не установлен [yarn](https://yarnpkg.com/), вы можете заменить команду на `npm install`

#### ⚠️ **`WARN`**: Не забудьте настроить переменные окружения `.env` на основе `.env.example`:

### **3. Запуск Backend**

```bash
docker compose build
docker compose up -d
```

#### 💡 **`TIP`**: Убедитесь, что у вас запущен [Docker Engine](https://docs.docker.com)

####

### **4. Настройка Frontend**

```bash
cd frontend
yarn
```

#### 💡 **`TIP`**: Убедитесь, что вы вернулись в корневую директорию перед выполнением команды `cd frontend`

#### 💡 **`TIP`**: Если у вас не установлен [yarn](https://yarnpkg.com/), вы можете заменить команду на `npm install`

#### ⚠️ **`WARN`**: Не забудьте настроить переменные окружения `.env` на основе `.env.example`

### **5. Запуск Frontend**

```bash
yarn start
```

#### 💡 **`TIP`**: Для работы на мобильным приложении установите [Expo Go](https://expo.dev/go)

## 📱 Демо:

### 1. Страница авторизации

![ㅤ](https://github.com/Wo0zZ1/Unolingo/raw/main/assets/registration.PNG)

### 2. Страница профиля

![ㅤ](https://github.com/Wo0zZ1/Unolingo/raw/main/assets/profile.PNG)

### 3. Страница статистики

![ㅤ](https://github.com/Wo0zZ1/Unolingo/raw/main/assets/statistic.PNG)

### 4. Страница выбора уровня

![ㅤ](https://github.com/Wo0zZ1/Unolingo/raw/main/assets/map.PNG)

### 5. Страница теории

![ㅤ](https://github.com/Wo0zZ1/Unolingo/raw/main/assets/theory.PNG)

### 6. Страницы прохожения уровня

![ㅤ](https://github.com/Wo0zZ1/Unolingo/raw/main/assets/wordPicker.PNG)
![ㅤ](https://github.com/Wo0zZ1/Unolingo/raw/main/assets/textInput.PNG)

### 7. Страница результатов прохождения уровня

![ㅤ](https://github.com/Wo0zZ1/Unolingo/raw/main/assets/levelComplete.PNG)

## 📄 Лицензия

Copyright © 2025 [Wo0zZ1](https://github.com/Wo0zZ1)\
Этот проект использует [MIT](LICENSE) лицензию
