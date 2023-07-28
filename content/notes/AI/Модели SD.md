
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
- CyberRealistic https://civitai.com/models/15003/cyberrealistic?modelVersionId=114429
- 

##### Дизайнерские
- [MotionDesignV1 (3Dart,C4D style)](https://civitai.com/models/92770/motiondesignv1-3dartc4d-style)
- [Product Design (minimalism-eddiemauro)](https://civitai.com/models/23893/product-design-minimalism-eddiemauro)
- https://civitai.com/models/100056/bdicon
- https://civitai.com/images/1458724?modelVersionId=112777&prioritizedUserIds=5815&period=AllTime&sort=Most+Reactions&limit=20
- https://civitai.com/models/115188/hylv6 — капельки пурпура
- https://civitai.com/models/7884/graphic-art

обязательно затестить
https://civitai.com/models/97808/pseudo-flex-base 
- MotionDesignV1 — https://civitai.com/models/92770/motiondesignv1-3dartc4d-style
- graphic-art — https://civitai.com/models/7884/graphic-art
- ColorfulSurrealismAI https://civitai.com/models/12437/colorfulsurrealismai
- 2.8D STABLE BEST VERSION — https://civitai.com/models/77446/28d-stable-best-version
- StretchScape (широкие пейзажи) — https://civitai.com/models/99310/stretchscape
- Pirsus Artstation (дивописная) — https://civitai.com/models/97669/pirsus-artstation
- Pseudo Flex (Base) — https://civitai.com/models/97808/pseudo-flex-base
- AC pencil — https://civitai.com/models/20631/ac-pencil
- SDVN3-RealArt https://civitai.com/models/103160?modelVersionId=117136
- Abstract Photo — https://civitai.com/models/95973/abstract-photo
- 

Интересные
- Китайский комикс https://civitai.com/models/108598/7070s-chinese-comics
- 

Хрен с ним. Аниме
- https://civitai.com/models/105047/break-the-darkness
- 

##### Специальные
- [CharTurnerBeta](https://civitai.com/models/7252/charturnerbeta-lora-experimental)

Модели для ControlNet
- [QR-codes](https://huggingface.co/monster-labs/control_v1p_sd15_qrcode_monster/resolve/main/control_v1p_sd15_qrcode_monster.safetensors)
- https://civitai.com/models/90472?modelVersionId=96367

Модели для Inpaint

VAE