# Licenta_be
Be aferent proiectului de diploma

# .env
BASE_URL="http://localhost:${PORT}"
PORT=3000

DB_USER=admin
DB_PASSWORD=admin
DB_NAME=nestjs_db
DB_PORT=5432
PG_VOLUME=postgres_data
DATABASE_URL="postgresql://${DB_USER}:${DB_PASSWORD}@localhost:${DB_PORT}/${DB_NAME}"

GOOGLE_CLIENT_ID= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GOOGLE_CLIENT_SECRET= "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"
GOOGLE_CALLBACK_URL="${BASE_URL}/auth/google/callback"
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER= nistorsimona32@gmail.com
SMTP_PASS=cfqg eets grri kwux
SMTP_FROM="Fitness_app <nistorsimona32@gmail.com>"
JWT_SECRET="secret"
