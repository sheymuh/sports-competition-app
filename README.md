# Sports Competition App

Web-приложение для учёта результатов спортивных соревнований.

## Стек технологий

- **Backend:** Java 21, Spring Boot, Maven
- **Frontend:** React, Vite
- **CI/CD:** GitHub Actions
- **Контроль качества:** Checkstyle (Java), ESLint + Prettier (JS), Commitlint + Husky

## Структура проекта
```
sports-competition-app/
├── backend/ # Maven проект (Java 21)
├── frontend/ # Vite + React проект
├── .github/workflows # CI/CD пайплайны
└── README.md
```


## Требования

- JDK 21+
- Node.js 22.12+ (требование commitlint)
- Maven 3.9+ (или используйте `mvnw`)

## Запуск

### Backend
```bash
cd backend/sports-app
./mvnw spring-boot:run
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Соглашения по коммитам
Проект использует Conventional Commits.
Формат: &lt;type&gt;(&lt;scope&gt;): &lt;description&gt;

Примеры:
- feat(backend): add competition entity
- fix(frontend): correct results table rendering
- chore: update dependencies

Проверка сообщений коммитов настроена через Husky + Commitlint.