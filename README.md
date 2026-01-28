![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

## Voice Assistant with TTS

В данном репозитории представлен голосовой помощник с **TTS (Text-to-Speech)**, который распознает речевые команды из заданного списка, генерирует текстовые ответы с использованием языковой модели и преобразует текстовые ответы в речь с использованием **TTS-модели**. 

Для распознавания речи использовалась модель **Whisper large-v3**, для генерации ответов - **Saiga Llama-3-8B**, а для преобразования текста в искусственную речь - **snakers4/silero-models**.

Также в коде используется **JavaScript**, он нужен для того, чтобы в браузере (в **Google Colab**) записать звук с микрофона пользователя и вернуть его в **Python**-код в виде **base64**-строки. Соответственно, для работы с этим кодом потребуется предоставить доступ к микрофону и говорить свои промпты нашему ассистенту.

На выходе мы получаем расшифровку нашего промпта и ответ ассистента в виде текста и голосового сообщения.

> Рекомендую использовать **графический ускоритель T4** или мощнее!
