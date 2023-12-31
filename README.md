# BiometricAntiSpoofing

## Описание Проекта

`BiometricAntiSpoofing` - это система для обнаружения попыток обмана биометрических систем через анализ микродвижений лица и других характеристик. Проект улучшает безопасность биометрических аутентификационных систем, идентифицируя поддельные данные.

## Основные Характеристики

- **Обнаружение микродвижений лица:** Анализ для отличия настоящих лиц от изображений;
- **Анализ текстуры:** Выявление текстур экранов и печатных фотографий;
- **Обнаружение границ устройств:** Детекция рамок экранов;
- **Предобработка изображений:** Нормализация и коррекция перед анализом.

## Технологии

- Python, OpenCV, scikit-learn, TensorFlow/PyTorch
- Jupyter Notebook для анализа и тестирования ML

## Установка

```bash
git clone https://github.com/Artem-Olifirenko/BiometricAntiSpoofing.git
cd BiometricAntiSpoofing
pip install -r requirements.txt
```

## Использование

Запустите `main.py`, чтобы начать обработку бимоетрических данных в проекте:

```bash
python main.py
```

## Тестирование

Для запуска тестов выполните:

```bash
python -m unittest discover -s tests
```

## Лицензия

Этот проект лицензирован по лицензии BSD-3-Clause license. Смотрите файл `LICENSE` для получения дополнительной информации.



