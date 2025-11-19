# SlimeType - Endless Typing Practice

SlimeType is a minimal, browser-based typing practice tool designed to help you improve your speed and accuracy. It’s built with vanilla HTML, CSS, and JavaScript - no frameworks, no dependencies. Just open it in any modern browser and start typing.

## Features

- Real-time WPM (words per minute) and accuracy tracking
- Visual feedback: correct letters stay neutral, incorrect ones turn red
- Move between words with Enter or Backspace
- Skip a word with Enter, useful for pacing
- Press Tab anytime to reset with a new set of random words
- Clean, dark-themed interface optimized for focus
- No signups, no tracking, no ads - just typing

## How to Use

1. Open `index.html` in your browser.
2. Start typing the words as they appear.
3. Use **Enter** to skip to the next word.
4. Use **Backspace** at the start of a word to go back.
5. Press **Tab** anytime to get a fresh set of words.
6. When you finish, you’ll see your final stats - then press **New Test** to go again.

## Technical Notes

- The word list is drawn from common English words and some programming terms.
- Accuracy is calculated based on characters typed vs. expected, including extra or missing characters.
- WPM is calculated using the standard formula: (total characters / 5) / minutes elapsed.
- Errors are tracked - for example, typing a space mid-word counts as an error.
- The caret blinks to help you stay focused on your current position.

## Why This Exists

This started as a personal tool to practice typing without distractions. It’s intentionally simple but still easy to get lost in. another website also had a pretty ui.

## Credits

Created with care by Qwen3-coder and Kimi-K2, Made actually usable by me :p 🥇
