# 🐱 CatMath

Math practice for grade 5 with kittens. It runs in the browser, works offline, has no ads and collects no data.

**Open it:** https://smart-cat-space.github.io/catmath/

Languages: English (default), Polski, Русский, Українська — switch in ⚙️ Settings.

## What's inside

| Mode | What you do |
|---|---|
| ✖️ **Table** | Multiplication and division by 6, 7, 8, 9 (other numbers can be added), with an optional time limit per answer |
| 🧩 **Crossword** | 3×3 multiplication crossword: every row and column is a multiplication |
| 🔍 **Divisors** | Tap every divisor of a number, or 🌳 factorize it with the column method (60 \| 2, 30 \| 2, 15 \| 3, 5 \| 5) |
| 🐾 **Jumper** | Jump onto the platform with the right answer |
| ⚡ **Dash** | Jump over wrong answers, run through the right one |

Topics for Jumper and Dash (choose in Settings): times tables, order of operations, division with remainder, fractions, divisors and prime numbers, GCD and LCM, prime factors.
The wrong answers are typical mistakes (e.g. 2/7 + 3/7 = 5/14, or 19 + 5 · 7 = 168), so a quick guess doesn't work.

Correct answers earn kittens: every 3 in Table, every 5 in the games, and one for each solved crossword or divisor task. The 📊 Statistics screen shows where the mistakes are: a heat map of the times table, the hardest examples, results per topic and the history of each session. Examples that were answered wrong come back more often.

## Install on a phone

1. Open the link in Chrome (Android) or Safari (iPhone).
2. Chrome: menu ⋮ → **Add to Home screen** / **Install app**. Safari: Share → **Add to Home Screen**.
3. CatMath now has its own icon and works without internet.

## Privacy

Everything stays on the device. Progress is saved in the browser's local storage; nothing is sent anywhere. Clearing the browser data resets the progress.

## Po polsku

CatMath to aplikacja do ćwiczenia matematyki w klasie 5 (tabliczka mnożenia, krzyżówki, dzielniki, rozkład na czynniki, NWD i NWW, ułamki, kolejność działań, dzielenie z resztą) w formie gier z kotkami. Działa w przeglądarce i bez internetu, bez reklam, nie zbiera żadnych danych. Język polski można wybrać w ⚙️ Ustawieniach.

## Development

The whole app is one file, [`index.html`](index.html), with no build step and no dependencies. `sw.js` and `manifest.webmanifest` make it installable and available offline. When changing files, bump `CACHE` in `sw.js` so phones pick up the new version.

## License

[Apache License 2.0](LICENSE)
