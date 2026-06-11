# Кредиты источникам

«Живое слово» (zhivoe-slovo) — синтез идей из семи открытых скиллов, каждый под лицензией MIT. Контент этого репозитория написан заново (оригинальная редакция и компоновка), но идеи и подходы заимствованы. Спасибо авторам.

| Источник | Автор | Что взято |
|---|---|---|
| [ilyautov/humanizer-ru](https://github.com/ilyautov/humanizer-ru) | Ilya Utov | 20 HARD BANS, статистическая теория (perplexity, burstiness, контрастное вычитание), quad-pass аудит, предупреждение о гомогенизации, macro-burstiness, фингерпринты 2025-2026 |
| [SergeNS-mne/humanizer-ru](https://github.com/SergeNS-mne/humanizer-ru) | Sergey Starikov | голосовой паспорт `.humanizer/voice.json` и его эволюция, жанровые пресеты, вычислимые структурные метрики (плотность тире, σ длин предложений, listicle), нюансная политика тире |
| [Vladimir-Human/humanizer-ru](https://github.com/Vladimir-Human/humanizer-ru) | Vladimir | модульная архитектура (карта + references), дерево решений, шкала 🔴🟡🟢, regex чат-бот-артефактов, проверка подлога источников, каталог false-positives |
| [smixs/humanizer-ru](https://github.com/smixs/humanizer-ru) | Serge Shima | редакторская традиция (Нора Галь, инфостиль): «вернуть голос», а не «обмануть детектор» |
| [blader/humanizer](https://github.com/blader/humanizer) | Siqi Chen | раздел PERSONALITY AND SOUL, блок «что НЕ флагать» и «признаки живого письма», цикл черновик→аудит→финал (на базе Wikipedia: Signs of AI writing) |
| [aplaceforallmystuff/the-antislop](https://github.com/aplaceforallmystuff/the-antislop) | Jim Christian | тест-гороскоп, tiered scoring |
| [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) | Hardik Pandya | восемь базовых правил, scoring-рамка по пяти измерениям |

Первоисточник большинства паттернов — [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) (WikiProject AI Cleanup) и её русский аналог «Признаки сгенерированности текста».

## Ключевое отличие синтеза

Все источники, банящие тире наглухо (ilyautov, stop-slop, blader), здесь скорректированы: политика тире строится на плотности, жанре и голосе автора (подход SergeNS), потому что для русского — особенно для художки, публицистики и личных постов — слепой запрет тире вредит. Это центральное решение, которое и оправдывает отдельный репозиторий.
