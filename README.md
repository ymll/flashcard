# Simple Random Flashcard Reviewer

A single-file flashcard application designed for quick deployment on GitHub Pages. It allows users to input their own term/definition pairs and reviews them in a randomized order. All card data and user preferences are saved locally in the browser (`localStorage`) for simple setup.

## 🚀 Features

1. Single-File Deployment: All HTML, CSS (Tailwind), and JavaScript are in one index.html file.

1. Persistent Custom Data: Edit and save your flashcards; the data remains local to your browser across sessions.

1. Randomized Review: Cards are shuffled into a new random order every time you start a review session.

1. Click-to-Flip/Next: Simple, intuitive navigation. Keyboard works too: Space / Enter / → flips or advances, ← goes back, Esc closes a pop-up.

1. Know It or Not: While reviewing, mark each card "✓ I knew it" or "✗ Didn't know". The progress line keeps count, the finish screen shows your score, and "Try Again" re-reviews just the cards you missed.

1. Share by Link: Share a deck with one link. Links use URL-safe encoding, and links shared from older versions still open.

1. Export / Import: Save a deck as a `.json` file from the Edit Cards screen, and load one back from a file (also accepts `Term | Definition` lines).

1. Font Size Controls: Easily adjust text size (A+/A-) for better readability and accessibility (especially useful for young learners).

1. Responsive Design: Optimized for mobile phones and tablets.

1. Works Offline-ish: Cards and preferences are saved in the browser. If browser storage is unavailable (e.g. private mode), the app still starts and runs — it just won't remember things between visits.

## 🛠️ How to use

1. Go to https://ymll.github.io/flashcard.

1. Start learning!


## 💡 Usage

1. **Edit Cards:** Click the Edit Cards button. Enter one flashcard per line, using a vertical pipe (|) to separate the term and definition (e.g., Term | Definition).

1. **Start Review:** Click Start Review.

1. **Flip:** Click the card to see the definition. Or press Space / Enter / →.

1. **Next:** Click the flipped card again to advance to the next random card. Press ← to go back.

1. **Mark it:** While reviewing, tap "✓ I knew it" or "✗ Didn't know". Marks move you to the next card. At the end, "Try Again" re-reviews only the ones you missed; "Start Over" restarts the whole deck.

1. **Adjust Size:** Use the A+ and A- buttons in the top-right corner to adjust the card font size.

1. **Reset:** Use the Home button in the top-left to return to the launch screen.

1. **Share:** Tap the share button (bottom-right). Copy Link always works; WhatsApp / Telegram / Facebook open anywhere; Signal and SMS are offered on phones, where they can open.

1. **Back up a deck:** In Edit Cards, use Export deck (.json) to download your cards, and Import deck (.json) to load a deck file back in.