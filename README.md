# Personal Finance Assistant

Система для учёта, анализа и прогнозирования личных финансов на базе **Telegram-бота и Telegram Mini App**.

Telegram-бот используется для быстрого добавления операций и повседневных действий, а Mini App — для работы с транзакциями, аналитикой, бюджетами и прогнозом расходов.

## Интерфейс

<p align="center">
  <img src="docs/screenshots/bot-start.png" width="23%">
  &nbsp;
  <img src="docs/screenshots/miniapp-home.png" width="23%">
  &nbsp;
  <img src="docs/screenshots/transactions.png" width="23%">
  &nbsp;
  <img src="docs/screenshots/analytics-categories.png" width="23%">
</p>

<p align="center">
  Telegram-бот · Главная · Транзакции · Аналитика
</p>

### Telegram-бот

<p align="center">
  <img src="docs/screenshots/bot-menu.png" width="70%">
</p>

Через Telegram-бота можно быстро добавлять доходы и расходы, смотреть баланс и историю, импортировать банковские выписки и экспортировать данные в Excel.


### Аналитика и прогнозирование

<br>

<p align="center">
  <img src="docs/screenshots/analytics-changes.png" width="30%">
  &nbsp;
  <img src="docs/screenshots/analytics-period.png" width="30%">
  &nbsp;
  <img src="docs/screenshots/analytics-days.png" width="30%">
</p>

<p align="center">
  Прогноз расходов · Сравнение периодов · Расходы по дням
</p>

<p align="center">
  <img src="docs/screenshots/forecast.png" width="40%">
</p>



## Возможности

- учёт доходов и расходов;
- история, поиск и фильтрация транзакций;
- аналитика и графики;
- бюджеты и прогнозирование расходов;
- импорт банковских PDF-выписок;
- экспорт данных в Excel;
- автоматическая категоризация расходов;
- шаблоны операций и напоминания;
- REST API и административная панель.

**Стек:** Python, aiogram 3, Django, Django REST Framework, PostgreSQL, JavaScript, Chart.js, scikit-learn, openpyxl, XlsxWriter.

## Запуск проекта

```bash
git clone https://github.com/Vlad-gw/personal-finance-assistant.git
cd personal-finance-assistant

python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
