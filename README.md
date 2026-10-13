# Feed the Animals – spelling practice

A spelling game for young children. The game reads a word aloud in a British English voice, the child spells it on a big on-screen keyboard, and each correct word earns a treat to feed an animal.

Each player has her own words, her own animals and her own treat counts:

| Player | Animals |
|---|---|
| Ava | Momo the monkey, Pip the guinea pig, Bao the panda |
| Izzy | Pebble the guinea pig, Bean the capybara, Moss the sloth |

Players and animals are set in the `PLAYERS` list near the top of the script in `index.html`.

Everything is in one file, `index.html`. It has no install, no account and no internet calls.

## Adding this week's words
1. Tap **⚙️ Grown-ups** (top right).
2. There is a box for each child. Type one word per line. To have a word read the way a spelling test reads it (word, sentence, word), add a sentence after a `|`:
   ```
   said
   because | I smiled because it was sunny
   friend
   ```
3. Tap **Save spellings**. The words stay on that tablet until you change them.

Use the **Voice** drop-down to choose a British voice; it's marked "(woman)" or "(man)" where known. To get more voices, follow the steps on the settings screen for iPad or Android.

## How a round works
- The words come in a random order. The 🔊 button repeats the word and 🐌 says it slowly.
- **Right first time:** confetti, then she chooses an animal and a treat to feed it.
- **Wrong once:** "Have another go", and the word is read again.
- **Wrong twice:** the game shows her attempt, with the correct letters in green, next to the real word. She taps **Hide it** and writes it from memory. The word then comes back once more at the end of the round.
- The end screen shows stars and lists any words to keep practising.

## Putting it on the tablet
The file needs to be opened from a web address. Opening it straight from the Files app doesn't work reliably. Once it is hosted (for example on GitHub Pages), open the link in Safari (iPad) or Chrome (Android). Then use **Share → Add to Home Screen** on iPad, or **⋮ → Add to Home screen** on Android, so it opens full-screen like an app.

Note: words and treat counts are saved separately on each device, and separately for the Home Screen app and the browser tab.
