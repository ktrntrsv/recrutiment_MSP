# Сбор статистики из базы данных Notion в Google Spreadsheets
### Для мониторинга воронки принятия преподавателей Школы Программистов

To run the program

1. Create `.env` file that should contain `NOTION_BOT_TOKEN` variable.
2. Create directory `access_files` with `credentials.json` for Google Spreadsheets api.
3. Edit `config.py` if you need.
---
If you want to start default running, run
`python3 main`

If you want to run Spb running (to "Питер" table), run
`python3 main --spb`