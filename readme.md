# Скрипты для работы с API Тинькофф Инвестиций
## Возможности
1. Скачать котировки за год для компании по тикеру
```
$ python donwload-historical-data.py
```
Котировки загрузятся в формате ZIP в ту же директорию. В архиве -- CSV файлы в формате `<UID инструмента>-<Дата и время>-<High>-<Low>-<Open>-<Close>-<Volume>`

2. Можно использовать функции volatility and plotClosePrices модуль volatility_module

3. Проанализировать волатильность инструмента и его ожидаемую доходность за заданный период. Построить график цен
```
$ python analysis-of-volatility.py
```
