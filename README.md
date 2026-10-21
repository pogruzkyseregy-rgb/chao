# Чам

Игра: ингредиенты падают сверху, персонаж с ведёрком их ловит. Три промаха — уровень заканчивается и блюдо готово.

## Структура

- `www/index.html` — игра (прототип на canvas)
- `www/assets/` — картинки: `hero.png`, `ing1.png`…`ing8.png`, `dish_pot.png`
- `capacitor.config.json` — настройки Capacitor
- `.github/workflows/android.yml` — сборка debug APK при пуше в `main`

## Сборка APK

Каждый пуш в `main` запускает workflow. Готовый APK лежит в Actions → последний запуск → Artifacts → `chao-debug-apk`.
