# Проект: Fine-tuning Whisper для болгарской речи

Коротко о том, что сделано:
- Собраны и подготовлены датасеты (реальные записи + синтетические данные).
- Сформированы манифесты и подготовлены данные для обучения ASR. (в открытом доступе данных очень мало)
- Дообучили Whisper и сохранили лучшие чекпоинты по качеству. (до дообучения виспер смолл имел WER 0.44 после 0.077, wer виспера лардж на той же выборке 0.15)
- Проверили качество модели на валидации и тесте.

## Модель на Hugging Face
- Репозиторий модели: https://huggingface.co/danilovabg/wisper_small_fine_tune_bg
- Быстрый тест модели: https://huggingface.co/danilovabg/wisper_small_fine_tune_bg

## Данные
- Ссылка на Google Drive: 
https://drive.google.com/file/d/1nkEJG7onWfzU0zP4eHHMa9L4NxPd4xih/view?usp=drive_link