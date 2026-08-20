# NanoAI — проект для AndroidIDE

Это нативный Android-клиент для твоего NanoAI. Модели не скачиваются на телефон: запросы идут в API провайдеров.

## Что поддерживается
- OpenRouter — большинство моделей из исходного bot.py
- Gemini — Gemini-2.5-Flash
- Groq — Qwen3.6-27B
- Hugging Face — поле ключа подготовлено; текущий UI использует модели через OpenAI-compatible провайдеры.

## Сборка на телефоне
Открой папку проекта в AndroidIDE и выполни обычную сборку APK (Build/Assemble Debug).

После сборки APK будет в:
`app/build/outputs/apk/debug/app-debug.apk`

Важно: это именно Android-проект, а не APKTool M-проект. APKTool M можно использовать уже после получения APK.

API-ключи вводятся внутри приложения через ⚙.


## Android Code Studio / Redmi 13C
Проект совместим с Android Code Studio. Для сборки рекомендуется JDK 17.
Код `MainActivity.java` менять для переноса в Android Code Studio не требуется.
