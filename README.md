# ModemLocation - Система мониторинга локации модемов

Бэкенд-приложение на Spring Boot + PostgreSQL, упакованное в Docker. Автоматически принимает метрики и подтягивает геокоординаты.

## Как запустить проект

Для запуска вам понадобятся только установленный **Git** и **Docker Desktop**.

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/alexeysh521/ModemLocation.git
   cd ModemLocation
   ```
2. **В корне проекта у файла `.env.erase` удалить `.erase`, вместо `YOU_TOKEN_OpenCell` добавить свой токен, чтобы его получить зарегистируйтесь на `OpenCelliD`. Порт `8080 (по умолчанию)`, вы можете изменить на любой**
3. **Запустите проект одной командой**
   ```bash
   docker compose up -d --build
   ```
   
<img width="1283" height="971" alt="image" src="https://github.com/user-attachments/assets/c13c3247-a912-4f66-85c0-0bb9b5f65eba" />
<img width="1278" height="924" alt="image" src="https://github.com/user-attachments/assets/0af6733c-6672-4e87-920e-f543a189d448" />
<img width="1282" height="914" alt="image" src="https://github.com/user-attachments/assets/3d3c184b-cbb0-4983-9da6-c2e46307496a" />
