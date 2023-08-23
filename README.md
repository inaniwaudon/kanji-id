# kanji-id

kanji-id is a JavaScript library to generate unique ID using Han characters (kanji).

The kanji candidates use the common-use kanji (joyo-kanji, 2,136 characters). Since the length of id is 11 digits, there are 4.2229285 × 10^36 possible patterns.

## Install

```bash
# npm
npm install kanji-id

# yarn
yarn add kanji-id
```

## Usage

```ts
import { generateKanjiId } from "kanji-id";

generateKanjiId();
// 累距恣頻凶箸誌飽募祭古
```
