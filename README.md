# 🔤 Missing Letters Quiz

A fun and interactive vocabulary game that helps you learn English words by completing missing letters.

The game is built with **HTML, CSS, and JavaScript** and runs directly in your browser — no backend or installation required.

## 🎮 Features

- 🔤 Fill in the missing letters in English words
- 🖼️ Add pictures to your vocabulary
- 🌍 Automatic Arabic translation
- 🇪🇬 Arabic meanings for vocabulary
- 🔊 Listen to the pronunciation of words
- 💡 Hint system
- 🎯 Practice your mistakes
- ⭐ Score system
- 🎉 Celebration effects and sounds
- 📱 Responsive design for different screen sizes
- 💾 Automatically saves your words and settings in the browser
- ✏️ Add your own vocabulary
- 🗑️ Delete individual words or all words
- 🔠 Choose how many letters to hide
- 🎲 Random missing letters mode
- 📝 Choose the number of questions
- 🔡 Optional letter-choice buttons
- 🖼️ Support for image URLs, pasted images, and uploaded photos

## 🕹️ How to Play

1. Open the game.
2. Click **Start Quiz**.
3. Look at the picture and Arabic meaning.
4. Complete the missing letters.
5. Click **Check ✅**.
6. Get your score and review your mistakes.
7. Practice your mistakes again if needed.

## ⚙️ Custom Vocabulary

Click the ⚙️ **Settings** button to add your own words.

You can enter:

- **English word** — for example: `cat`
- **Arabic meaning** — for example: `قطة`
- **Picture** — paste an image URL, upload a photo, or paste an image from your clipboard.

If you leave the Arabic meaning empty, the game attempts to translate the word automatically.

## 🎯 Quiz Settings

You can customize the quiz with:

| Setting | Options |
|---|---|
| Letters to hide | Auto / 1 / 2 / 3 / Random |
| Questions | 5 / 10 / 20 / All |
| Letter choices | Off / 3 / 6 / 10 extra letters |
| Picture fit | Cover / Contain |
| Arabic meaning | Show / Hide |
| Pronunciation | On / Off |

## ⭐ Scoring

A correct answer gives:

- **+1 point** for a normal correct answer
- **+0.5 point** when a hint was used

Wrong answers are shown after checking so you can learn from your mistakes.

## 🔊 Sounds

The game includes browser-generated sound effects:

- 🎵 Correct-answer sound
- 🏆 Quiz-completion celebration
- 💨 Whoosh effect
- ❌ Soft wrong-answer sound

It also uses the browser's **Speech Synthesis API** to pronounce English words.

## 💾 Data & Privacy

Your vocabulary and quiz settings are stored locally in your browser using `localStorage`.

The game does not require a database or server.

Your saved vocabulary uses the browser storage keys:

```text
vocab-v2
vocab-settings-v2
```

## 🌐 Automatic Translation

The game first checks its built-in vocabulary database.

If a word is not found, it attempts online translation using:

1. Google Translate endpoint
2. Lingva
3. MyMemory

Online translation may not work if the browser or hosting environment blocks external requests.

## 🚀 Run Locally

No build system
