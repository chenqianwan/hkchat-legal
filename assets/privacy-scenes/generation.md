# 隱私挑戰：生成場景圖片

使用內建 imagegen 工具生成三張虛構場景圖片，再轉為 WebP 供手機頁面使用。人物、學校及聯絡資料均為情境演示素材；網頁的遮擋層由互動控制。

## 二手開箱

[場景圖片](privacy-trade.webp)

最終生成提示詞：

```text
Use case: photorealistic-natural.
Asset type: landscape photograph for a Hong Kong mobile privacy education game, fictional scene.
Primary request: create a realistic second-hand headphones unboxing photo, not a vector illustration, not a UI mockup.
Composition: landscape 3:2, camera nearly straight down at a tidy pale wood apartment table. On the LEFT third is a small opened brown cardboard parcel with a large white shipping label facing the camera. In the CENTER are unbranded over-ear headphones and their open packaging. On the RIGHT is a smartphone lying upright vertically, entire screen visible, showing a simple fictional seller profile / transaction.
Privacy clues must be separate and easy to cover with rectangular overlays later. On the parcel label place the telephone line at about x=23%, y=35%, with exact large legible text "電話 1234 5678"; underneath at about x=23%, y=54% place "晴嵐苑 8樓 8B". Leave space between these two lines. Do not add any other identifying label text or barcodes. On the phone screen put a clearly visible small portrait of a fictional East Asian adult above the exact name "何樂", grouping both within x=76–93%, y=28–68%. Lower phone screen can have a minimal headphones thumbnail but no extra personal details.
Natural Hong Kong home daylight, real cardboard grain, believable phone glass, soft neutral colors with very subtle lavender packaging accent. Clean, plausible candid lifestyle photo with a clear subject, sharp enough for a mobile screen.
Only invented people and sample data. No real brand logos, no watermarks, no captions, no redaction, no circles, no callout boxes, no UI borders outside the actual smartphone. Do not create a collage. Keep all clue areas fully inside the frame.
```

## 屋苑走廊

[場景圖片](privacy-hall.webp)

最終生成提示詞：

```text
Use case: photorealistic-natural.
Asset type: landscape photo for a Hong Kong mobile privacy education game, fictional apartment corridor scene.
Primary request: a realistic phone snapshot in the corridor outside a Hong Kong apartment, showing cartons left in the shared corridor and one neighbor. Not an illustration or UI mockup.
Composition: landscape 3:2, eye-level view. A closed pale wood apartment door occupies the left half, with a metal door-number plaque reading exactly "8B" placed around x=24%, y=24%. Two cardboard delivery boxes sit in the lower center, still clearly obstructing part of the corridor. A white courier label faces the camera on the front box, with one readable line "電話 1234 5678" centered around x=43%, y=73%. On the RIGHT stands a single fictional East Asian adult neighbor wearing ordinary muted blue casual clothes, their full face clearly visible around x=77%, y=36%. No other people, faces or reflections.
Make door number, face and telephone spatially separate for individual rectangular redaction overlays. Plaque occupies no more than x=17–33%, y=17–30%; entire face and hair within x=68–85%, y=19–45%; courier label within x=31–55%, y=64–83%.
Natural indoor daylight, familiar tiled Hong Kong residential corridor, slightly used cardboard and genuine materials, neutral warm tones, tidy photographic composition.
Only fictional people and sample data. No real residential building name, no extra personal info, no logos, no watermarks, no captions, no existing blur or censoring, no callout boxes or graphic overlays. Keep privacy clues fully inside the frame.
```

## 學校活動

[場景圖片](privacy-school.webp)

最終生成提示詞：

```text
Use case: photorealistic-natural.
Asset type: landscape photograph for a Hong Kong mobile privacy education game, fictional school activity scene.
Primary request: a warm natural group photograph of exactly TWO fictional East Asian primary school children, one girl and one boy around 9 years old, at a small after-school arts and crafts activity. Fully clothed in casual lavender and sage T-shirts, seated at a craft table with colored paper, in a bright Hong Kong community classroom. Not an illustration or UI mockup.
Composition: landscape 3:2. The children's clearly recognizable smiling faces are well separated and fully visible: girl centered x=32%, y=40%; boy centered x=68%, y=40%, each head within x=center±12%, y=24–54%. Each child has a white rectangular NAME STICKER on their chest, girl's sticker at x=32%, y=68% reading exactly "曉晴", boy's sticker at x=68%, y=68% reading exactly "子朗". In the top LEFT background, a flat small activity sign at x=6–45%, y=4–19% reads exactly "星橋小學 · 三年甲班". The sign is clearly separated from faces.
Make the two faces, two name stickers and school sign distinct and unobstructed, easy to mask later using rectangular overlays. No other people or faces, no reflective surfaces, no other identifying text. Keep paper crafts below y=78%.
Natural window light, authentic skin and fabric textures, inviting educational setting, realistic candid photograph with clean framing.
All people and school information are fictional. No real school crest, logos, watermarks, captions, redaction, blur, graphic callouts, or UI. One cohesive photo, not a collage.
```

