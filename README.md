# YandexGPT Summarize

![GitHub release (latest by date)](https://img.shields.io/github/v/release/NKDev/YandexGPT-Summarize)
![GitHub license](https://img.shields.io/github/license/NKDev/YandexGPT-Summarize)
![GitHub issues](https://img.shields.io/github/issues/NKDev/YandexGPT-Summarize)

**YandexGPT Summarize** — это скрипт для Tampermonkey, который добавляет плавающую кнопку на любую веб-страницу. Одним кликом вы можете отправить URL статьи или видео на сервис [YandexGPT (300.ya.ru)](https://300.ya.ru) и получить краткое обобщение контента, без вставки своего api ключа.

---

## ✨ Возможности

- **Плавающая кнопка**: Появляется на всех сайтах и легко перемещается по экрану.
- **Интеграция с YandexGPT**: Открывает 300.ya.ru и автоматически передает текущий URL для обработки.
- **Поддержка видео и статей**: Работает с любым контентом, который поддерживает YandexGPT.
- **Сохранение позиции**: Ваше расположение кнопки запоминается между сессиями.
- **Уведомления об ошибках**: Встроенные сообщения об ошибках с автоматическим скрытием.

---

## 🚀 Установка

1. **Установите Tampermonkey**:
   - [Google Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
   - [Другие браузеры](https://www.tampermonkey.net/)

2. **Установите скрипт**:
   - Нажмите на кнопку ниже, чтобы установить скрипт напрямую:  
     [![Install]()](https://github.com/NikitaKrulov/TampermonkeyYaGPT)

3. **Готово!** Откройте любой сайт, и вы увидите плавающую кнопку в правом нижнем углу.

---

## 🛠️ Как это работает

1. На любом сайте нажмите на плавающую кнопку с логотипом YandexGPT.
2. Откроется новая вкладка с сервисом [300.ya.ru](https://300.ya.ru), куда автоматически передается текущий URL.
3. YandexGPT обработает страницу и выдаст краткое содержание.
