# kaggle-titanic

Соревнование: https://www.kaggle.com/competitions/titanic

## Результат
Public score: 0.78229  
Скрин отправки: `submission.png`

## Что сделано
- Загрузка train/test
- Предобработка: заполнение пропусков (median/most_frequent), one-hot encoding
- Формирование `submission.csv` и отправка на Kaggle

## Как запустить/воспроизвести
1) Скачать данные с Kaggle (train.csv, test.csv) со страницы соревнования (вкладка Data)
2) Открыть `titanic.ipynb` и выполнить все ячейки
3) На выходе будет создан `submission.csv`

## Файлы
- `titanic.ipynb` — ноутбук с кодом
- `submission.csv` — файл для отправки на Kaggle 
- `submission.png` — подтверждение score
