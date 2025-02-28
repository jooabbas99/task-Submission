# Project Setup Guide

## Submission Video

This video demonstrates the final output of the project.

The video file is available in the repository at:

```
/submission-video.mkv
```

You can play it using any media player or view it directly in your code editor if supported.

---

## How to Run the Project

### Backend (Laravel)

#### 1. Clone the Project

```bash
git clone https://github.com/jooabbas99/laravel-realworld-example-app
cd laravel-realworld-example-app
```

#### 2. Ensure PHP Version

Make sure your PHP version is **8.1**.

#### 3. Configure Environment

```bash
cp .env.example .env
```

Modify the `.env` file according to your database and application settings.

#### 4. Install Dependencies

```bash
composer install
```

#### 5. Run Database Migrations

```bash
php artisan migrate
```

#### 6. Run the Project

```bash
php artisan serve
```

The backend will be available at `http://127.0.0.1:8000/`.

---

### Frontend (React or Vue)

#### 1. Clone the Project

```bash
git clone https://github.com/jooabbas99/react-query-realworld
cd react-query-realworld
```

#### 2. Modify API Host URL

Open the file:

```bash
/src/repositories/apiClient.ts
```

Ensure the API base URL matches the backend:

```javascript
const host = "http://127.0.0.1:8000/api";
```

#### 3. Install Dependencies

```bash
npm install
```

#### 4. Build the Project

```bash
npm run build
```

#### 5. Start the Project

```bash
npm run start
```

The frontend will be available at `http://localhost:3000/` (or the default port used by your framework).

---

## Notes

- Ensure that both backend and frontend are running simultaneously.
- If you face issues, check the `.env` file configurations and API routes.
