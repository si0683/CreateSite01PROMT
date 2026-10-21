# AGENTS.md — правила для ИИ-агентов

Общий промт урока «Создаём сайт»: ученик выбирает тему, стиль и цвет, Qwen берёт готовый шаблон одного из шести сайтов
(Pizzeria, GameStore, ClothesShop, Confectionery, ToyStore, DanceSchool — github.com/si0683/<имя>, папки в D:\8Lending\sites\tetrika).

- Весь промт — ОДИН блок ````text в начале README.md. Ссылки на шаблоны — полные, отдельным блоком «ТЕМА: …» на каждый сайт: Qwen плохо подставляет части адреса.
- README.md создаёт генератор D:\8Lending\sites\tetrika\_generator (gen_docs.py, функция lesson_md). Правишь — правь там и перезапусти gen_docs.py, иначе правку затрёт.
- Стиль и цвет применяются строками `style` и `color` в объекте `LAB` в script.js сайтов; поменялся `LAB` — обнови промт.
- Похожий общий промт для игр — github.com/si0683/CreateGame01PROMT.
