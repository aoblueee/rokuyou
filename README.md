# rokuyou

Fantastical などのカレンダーアプリで購読するための六曜カレンダーです。

## 表示

毎日の終日予定として、次の形式で表示します。

- ⚪︎大安
- ⚪︎友引
- ⚪︎先勝
- ⚪︎先負
- ⚪︎赤口
- ⚪︎仏滅

収録期間: 2025-01-01 〜 2030-12-31

## Fantastical で購読

GitHub Pages を有効化した場合:

`https://aoblueee.github.io/rokuyou/rokuyou.ics`

Pages 有効化前は Raw URL でも購読できます:

`https://raw.githubusercontent.com/aoblueee/rokuyou/main/rokuyou.ics`

Fantastical の **Settings → Calendars & Lists → + → Add Subscription** に URL を貼り付けます。

## 六曜の算出

六曜は旧暦の月と日をもとに、一般的な配当規則
`(旧暦の月 + 旧暦の日) mod 6`
で算出しています。

余りは次の対応です。

| 余り | 六曜 |
|---:|---|
| 0 | 大安 |
| 1 | 赤口 |
| 2 | 先勝 |
| 3 | 友引 |
| 4 | 先負 |
| 5 | 仏滅 |

六曜は伝統的な暦注であり、科学的な吉凶を示すものではありません。
