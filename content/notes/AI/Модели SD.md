
Слово модели можно трактовать по-разному. Сейчас мы говорим о моделях для SD. У SD есть _базовые_ модели. Это те которые обучили в стабилити. Обучение базовой модели — это очень ресурсоёмкое дело, недоступное простому смертому. Но базовую модель можно дообучать на своих данных, тем самым улучшая качество генерации. Есть несколько способов дообучения моделей. Чаще всего, более сложные и ресурсоёмкие методы дают более качественный результат, а быстрые и лёгкие методы дают результат похуже. Однако, каждый метод хорош для решения своей узкой задачи. Результатом становится либо файл, который заменяет файл основной модели, либо файл, подключаемый дополнительно. 

Итак, есть несколько типов моделей. 
Самые базовые модели Stable Diffusion:
- SD v1.5
- SD v2.1
- SDXL

### Каталоги моделей
Два самых больших каталога, которые мне удалось найти к текущему моменту
- [Civitai](https://civitai.com/)
- [Huggingface](https://huggingface.co/spaces/huggingface-projects/diffusers-gallery)

Модели бывают нескольких типов. Вот ключевые
- Чекпоинты
- Лоры
- Текстурная инверсия (эмбединги?)
- Дримбув (?)

А здесь список моделей, которым я отдаю предпочтение

### Универсальные модели
- [reliberate](https://civitai.com/models/79754/reliberate) — реалистичная 
- [deliberate](https://civitai.com/models/4823/deliberate) — использую как дефолтную
- [LowRA](https://civitai.com/models/48139/lowra) — как фотки в низком ключе
- [Lit](https://civitai.com/models/51145/lit) — как фотки в высоком ключе

##### Дизайнерские
- [MotionDesignV1 (3Dart,C4D style)](https://civitai.com/models/92770/motiondesignv1-3dartc4d-style)
- [Product Design (minimalism-eddiemauro)](https://civitai.com/models/23893/product-design-minimalism-eddiemauro)
- https://civitai.com/models/100056/bdicon

##### Специальные
- [CharTurnerBeta](https://civitai.com/models/7252/charturnerbeta-lora-experimental)

Модели для ControlNet

Модели для Inpaint

VAE